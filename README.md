### Hi there 👋 

技術ログ -> [syk site](https://syksite.gatsbyjs.io/)

文章多めの書き物 -> [note](https://note.com/sayacan)




```
import React, { useState, useEffect } from 'react';

export function IntroduceMySelf () => {

  const [syk, newSyk] = useState('😆');
  const [mynote, setMyNoteURL] = useState('note');
  const [myLog, setMyLogURL] = useState('syk site');

  
  useEffect(() => {
    
    newSyk('software engneer!!!👩🏻‍💻💚');
    
    setMyNoteURL('https://note.com/sayacan')

    setMyLogURL('https://syksite.gatsbyjs.io/')
    
  }, []);
  
  return (
    <h1>
      I'm Sayaka, {syk}.
    </h1>
    
    <p>
      here -> {myLog} and {mynote}
    </p>
  );
};
```
