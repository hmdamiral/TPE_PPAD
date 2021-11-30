# TPE_PPAD
Programme à plusieurs noeuds utilisant le middleware Corba

liens vers la vidéo youtube : https://youtu.be/5XYWKcz1A30

## Python
- Install omniORB, test that it is available as Python package (import OMNIOrb).
- Go into the ./python subdirectory.
- (Optional) Re-generate stubs and skeletons with "omniorb -bpython ../echo.idl".
- Start the server with "python server.py". It will print the server IOR to be used by the client.
- Start the client with "python client.py <IOR>".
