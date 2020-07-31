<h1 align="center">Bus Reservation System</h1>

<p align="center">
<img style="padding:10px;" src="https://img.shields.io/badge/Open%20Source-💕%20-9cf?style=for-the-badge"><br>
<img style="padding:10px;" src="https://img.shields.io/github/contributors/souravmondaldev/Bus-Reservation-System?style=flat-square">
<img style="padding:10px;" src="https://img.shields.io/github/forks/souravmondaldev/Bus-Reservation-System?label=Forks&style=flat-square">
<img style="padding:10px;" src="https://img.shields.io/github/stars/souravmondaldev/Bus-Reservation-System?style=flat-square">
<img style="padding:10px;" src="https://img.shields.io/github/languages/count/souravmondaldev/Bus-Reservation-System?style=flat-square">
<img style="padding:10px;" src="https://img.shields.io/github/license/souravmondaldev/Bus-Reservation-System?style=flat-square">


This is a simple Bus Reservation System programmed using Cpp .This program allows you to add bus details,then you can reserve a bus seat according to vacant seat available.One can check for list for vacant seats in a bus.It also allows you to see the available bus for now.
This is a simple implementation of c++ code using class and structure. 

## How to run

Before running make sure you are having an c++ ide for windows users and g++ compiler installed for linux users.For windows user just open the file with any cpp ide and just compile and run.For unix users first navigate to the directory where this ```busrsm.cpp ``` file stored and then run the follwoing commands in terminal.

```C++
g++ [filename.cpp]
./a.out # unix
a.exe # windows
```
<img align="center" height="500" src="sm.png" alt="BusReservationSM"/>

## Usage

```CPP


  void addnewbus() # Used to add a new bus details

  void allotment(); #used to allot a set to an passenger

  void empty(); # to check if the buses are empty

  void show(); #shows avialble bus seats

  void avail(); #shows all avialable buses

  void position(int i); #to get the all reserved bus seats
```
## Cons
```file handling``` not added. A file system can make this block of code more reusable and complete. Any PR for ```file handling``` 
solution is appriciated 😊.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate. Feel free to contact here: souravmondal0341@gmail.com

## Credits
[SouravMondal](https://github.com/souravmondaldev)
