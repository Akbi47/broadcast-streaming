Broadcast Real Time Streaming Video And Audio Using Python,Socket... : pyaudio, pyshine,ffmpeg... 

Install Package Need To Use (In Files Project ): pip install 'module name'...
Run Files in sequence:
-------relate to server

	***** audio

	+Audio_Port_Server/audio-server.py
		python apserver.py

	***** video

	+Video_Port_Server/Original Server/video-server.py
		python oserver.py

	+Video_Port_Server/Cached Server/cache-server.py
		python cserver.py

------- relate to client
	+Client1/client.py
		python client.py
	+Client2/client.py
		python client.py

function: 
	+play real time live stream and audio
	+play real time live video source folder and music
