## Dependency
- `Numpy`
- `PILLOW`
- `torch torchvision tensorboardX` option

## Content
```
|-- Competition_3v3snakes           // https://github.com/jidiai/Competition_3v3snakes.git
    |-- env		                    // game environments
    |	|-- obs_interfaces		    // Super Class
	|	|	|-- observation.py		// support Grid interface
	|	|-- simulators		        // Super Class
	|	|	|-- game.py
	|	|	|-- gridgame.py         
	|	|-- config.ini		        // env config
	|	|-- chooseenv.py 
	|	|-- snakes.py
	|-- examples
	|   |-- random                  // random policy
	|   |   |-- submission.py       // you can submit this file to the platform without any modification
	|   |-- myagent                 // customize policy
	|   |   |-- dqn.py              
	|   |   |-- submission.py       // main file，which should contain function named `my_controller`
	|-- utils                       
	|-- run_log.py		            // run an episode and generate .json log
	|-- replay	                    // replay local util. Click replay.html and upload the json generated by run_log.py to replay 
```







