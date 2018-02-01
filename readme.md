Sample testing app with haproxy and nginx. 

	1. haproxy folder contents latest docker image of haproxy and haproxy simple configuration file.
	2. nginx folder contents of latest nginx image and a sample html file.
	3. docker-compose file contents to build them.
	4. curl_check file contents sequentially 20 request to haproxy server with the help of curl.
	5. check the shell file to change the sequence of the request.

Just put 

	$ docker-compose up

Then run the bash file from another command prompt window/tab

	$bash curl_check.sh