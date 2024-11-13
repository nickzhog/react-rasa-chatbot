# ML-Chatbot 

## Rasa 

### Deploy
```bash
cd rasa
LD_PRELOAD=/<PATH>/miniconda3/envs/test-env/lib/libgomp.so.1 rasa train 
LD_PRELOAD=/<PATH>/miniconda3/envs/test-env/lib/libgomp.so.1 rasa run --enable-api --cors "*"
```

## Frontend 

### Deploy
```bash
cd react
npm install
npm run build
npm run start
```