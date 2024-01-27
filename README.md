# Dodge the Emails and Meetings and Creeps
game built in godot, exported to html/wasm

## running the game
1. docker build -f docker/Dockerfile -t my-wasm-game-demo .
2. run the registry.sh command to build a local cluster in kind
3. run helper.sh to get certs 
5. kubectl apply -f deployment/kubernetes-deploy.tml

## playing the game
1. uses sslip.io to return a local address
2. navigate to mywasmgame.127.0.0.1.sslip.io to play the game
