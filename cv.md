# Katsiaryna Turliuk

## Contacts

* __Location:__ Minsk, Belarus
* __Phone:__ +375 29 832 45 39
* __Email:__ porg1995@gmail.com
* __GitHub:__ kittypaw95

## About Me

I decided to radically change my field of activity. And now I am improving in this direction.

## Skills

* HTML
* CSS
* JavaScript
* PHP
* SQL

## Code Example

> Constructor of “Flight” objects, containing the following properties: driver’s last name; car number 1234 AB-7; destination; lifting capacity (in tons). When entering data from the keyboard, the data is checked for accuracy.

```javascipt
	document.write("<table><tr><th>Фамилия водителя</th><th>Номер авто</th><th>Пункт назначения</th><th>Грузоподъемность(в тоннах)</th></tr>")
		
		var surname, numauto, destination, carrying;	
		function Flight()
		{
				 
				this.surname = surname;
			
				this.numauto = numauto;
		
				this.destination = destination;
				
				this.carrying = carrying;
		
		}
		Flight.prototype.showFlight = function(Flight)
		{

		return ("<tr><td>"+this.surname+"</td><td>"+this.numauto+"</td><td>"+this.destination+"</td><td>"+this.carrying+"</td></tr>");
		}
		
	var FlightArray = [];
	do {
        var surname = prompt("Введите фамилию водителя");
		if (typeof surname !== "string" || surname === null) 
		{
            break;
        }
		
        var numauto = prompt("Введите номер автомобиля формата 1234АВ-7(ESC, Отмена - окончание ввода данных):");
		
        if (numauto === null || +numauto == 0) 
		{
            break;
		}
			
        var destination = prompt("Введите пункт назначения");
		if (typeof destination !== "string" || destination === null) 
		{
            break;
        }
        
        var carrying = prompt("Введите грузоподъемность(в тоннах)");
		if (carrying === null || isNaN(+carrying)) 
		{
            break;
		}
		FlightArray = new Flight(surname, numauto, destination, carrying);
		console.log(FlightArray);


    } while (true);	
	
	for (var i in FlightArray)
	{
		document.write(FlightArray.showFlight());
	
	}
	
	document.write("</table>");
```

## Experience

## Education

* __University:__ School of Business and Management of Technology of BSU, programmer - web designer

## English

* __A2__
