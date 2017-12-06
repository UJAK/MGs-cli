Windows Minergate Console Client service extenstion
This is easy way to change your Minergate console client to managed service.

1.) Copy all files from this directory to directory C:\Program Files\MinerGate where is minergate installed by default.
	If you are installed MG-cli to other directory, you need edit "binpath" parametr in _install.cmd file.
2.) Run as administrator "_install.cmd". It create service "Minergate-cli".
3.) Edit service.conf file and set parametr for running.
	Example for local config: -user YOUR-EMAIL -bcn 2
	Example for remote service.conf: https://amadeus.ujak.cz/mg/my-service.conf
		(in web page must me only parameters as in local version)
		Example my-service.conf (same as local): -user YOUR-EMAIL -bcn 2
	Config will read every start of the service.

4.) Run service or restart PC, service startup automatic.


Mischa [it@ujak.cz]
Donate bitcoin: 1BD6WQiwSGh5N8jWcZVycroYTmn88mNrdz


