### Hi there 👋 
```
import React, { useState, useEffect } from 'react';

export function IntroduceMySelf () => {

  const [syk, newSyk] = useState('😆');
  const [myLog, setMyLogURL] = useState('note');
  
  useEffect(() => {
    
    newSyk('software engneer!!!👩🏻‍💻💚');
    
    setMyLogURL('https://note.com/sayacan/')
    
  }, []);
  
  return (
    <h1>
      I'm Sayaka, {syk}.
    </h1>
    
    <p>
      here -> {myLog}
    </p>
  );
};
```
