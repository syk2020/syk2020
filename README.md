### Hi there 👋 
```
import React, { useState, useEffect } from 'react';

export function IntroduceMySelf () => {

  const [syk, newSyk] = useState('😆');
  
  useEffect(() => {
    newSyk('software engneer!!!👩🏻‍💻💚');
  }, []);
  
  return (
    <h1>
      I'm Sayaka, {syk}.
    </h1>
  );
};
```
