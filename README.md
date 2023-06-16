<h1 align="center">BUILDING CHINESE CHESS AI ENGINE BY TYPESRCIPT</h1>

## Install
```bash
# clone
https://github.com/nqkhanh2002/China-Chess-AI.git
cd ChineseChessAI 

# Install dependencies
npm install

# start server
npm start

```
Open your browser, go to `http://localhost:3000/` and you should be good to go 

--------------
<br>

## Disclaimer
- AI algofithms in the backend computation engine need to be enchanced (I was a bit hasty when then poster session was approaching >\_<)
    - `MCTS` and `TDLearning` implementations are not solid
    - reinforcement learning part seldom works

- Effienciency need to be imporved
    - Current computation engine is in javascript, which is not fast enough (I did not know how to call other executables from nodeJS then..., but now I do, please see below)
    - You may implement a more powerful engine in C/C++ by calling a subprocess in server, [NodeJS Child Process](https://nodejs.org/api/child_process.html) should help
 
<br>

--------------

Thanks for your interest :)
<br><br>
