#### Simple example of using Jmeter testing https://swapi.dev/.
#### Download Jmeter https://jmeter.apache.org/download_jmeter.cgi
#### Clone repo:
```
$ git clone https://github.com/vsshk/jmeter-example-simple.git
$ cd jmeter-example-simple
```
Run for gui:
```
$ jmeter
```
and for non GUI 
```
$ jmeter -n -t starwarsapi.jmx
```
This will load https://swapi.dev with 1000 concurrent virtual users and 60 seconds of ramp time, method = GET, endpoint /api/people/1/.
* Please give it a "star" if it helped you.
