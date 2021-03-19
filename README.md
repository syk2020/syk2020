### Hi there 👋 
```
import React, { useState, useEffect } from 'react';

export function IntroduceMySelf () => {
  const [syk, newSyk] = useState('😆');
  useEffect(() => {
    newSyk('software engneer!!!👩🏻‍💻💚');
  }, []);
  render(
    <h1>
      I'm Sayaka, {syk}.
    </h1>
};
```
