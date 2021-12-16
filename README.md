# Capstone Hardware Simulation

A simple Web Application to plot the EEG Datapoints received from [EEG Signal Generator API](https://github.com/soumallyadev07/EEG-Signal-Generator-API), send the received data to the [Seizure Detection API](https://github.com/soumallyadev07/Seizure-Detection-API), get the result, plot it in the seizure graph, update the database and send an alert to a user in case of a Seizure using the [DB Notification Sender API](https://github.com/soumallyadev07/DB-Notification-Sender-API).

## Prerequisites
Get your PushBullet credential from the console and put it in place of "[UNIQUE_PushBullet_Token](https://github.com/soumallyadev07/Capstone-Hardware-Simulation/blob/ce8eabcbf63027972a64d637446b630006fcfa6f/index.html#L127)" in "index.html".

## Installation

* Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the requirements.
* Start 3 terminals and run the following apps according to their Readme files - 
    * [EEG Signal Generator API](https://github.com/soumallyadev07/EEG-Signal-Generator-API)
    * [Seizure Detection API](https://github.com/soumallyadev07/Seizure-Detection-API)
    * [DB Notification Sender API](https://github.com/soumallyadev07/DB-Notification-Sender-API)




### Usage

```bash
# Click on the index.html file after starting the 3 APIs
```
The application will be started and it will be opened in the Browser
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)