# Python Voice Chat
A program that allows multiple people to communicate over the internet using their microphones for voice chat. If you don't have Python or the required modules, you can download an .exe file for both the server and client [here.](https://github.com/TomPrograms/Python-Voice-Chat/releases/tag/0.1)

## Setup
- Dependancy Installation - ``pip install -r requirements.txt``
- Running - ``python client.py`` or ``python server.py``

## Usage
- Run server.py or server.exe specifying the port you want to bind to.
- If you intend to use this program across the internet, ensure you have port forwarding that is forwarding the port the server is running on to the server's machine local IP (the IP displayed on the server program) and the correct port.
- Clients can connect across the internet by entering your public IP (as long as you have port forwarding to your machine) and the port the machine is running on or in the same network by entering the IP displayed on the server.
- If the client displays ``"Connected to Server"``, you can now communicate with others in the same server by speaking into a connected microphone.

## Requirements
- Python 3
- PyAudio
- Socket Module (standard library)
- Threading Module (standard library)

## Contributing
Since this is a simple project, this repository is unlikely to be majorily changed, however if you wish to contribute with bug fixes/new features/code improvements, pull requests are welcome. Issues are also welcome if you want to discuss or raise an issue.

## License
[MIT](https://choosealicense.com/licenses/mit/)
