# Python Voice Chat
A program that allows multiple people to communicate over the internet using their microphones for voice chat.

## Setup
- Dependancy Installation - ``pip install -r requirements.txt``
- Running - ``python client.py`` or ``python server.py``

## Usage
- Run ``server.py`` on the machine you wish to act as the server, entering the desired port you wish to run the server on. You can run multiple independent servers, however they must be running on different ports.
- Any clients can now connect to the server by running ``client.py`` then entering the IP and port the server is running on (as seen in the server terminal).
- Clients can now communicate by speaking into a connected microphone.

## Requirements
- Python 3
- PyAudio
- Socket Module (standard library)
- Threading Module (standard library)

## Contributing
Since this is a simple project, this repository is unlikely to be majorily changed, however if you wish to contribute with bug fixes/new features/code improvements, pull requests are welcome. Issues are also welcome if you want to discuss or raise an issue.

## License
[MIT](https://choosealicense.com/licenses/mit/)
