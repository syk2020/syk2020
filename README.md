# Hi there 👋 

文章多めの書き物 -> [note](https://note.com/sayacan)


■ とあるコーディングスクールのいち卒業生が技術以外に得たものの話
■ The story of one graduate of a coding school who gained more than just skills (Japanese Only)
https://note.com/sayacan/n/na499301e9762

```
import React, { useState, useEffect } from 'react';

export function IntroduceMySelf () => {

  const [syk, newSyk] = useState('😆');
  const [myLog, setMyLogURL] = useState('note');
  
  useEffect(() => {
    
    newSyk('software engneer!!!👩🏻‍💻💚');
    
    setMyLogURL('https://note.com/sayacan')
    
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
