# Andrey Perovskiy 
********
## About and contacts
__Birsday:__ 01.08.1983


__Phone:__ +995593196623  
__E-mail:__ [EstSkif@gmail.com](EstSkif@gmail.com)  
__Telegram:__ @Est_01  
__Location:__ Batumi, Georgia  
__Website:__ [andreyp.pythonanywhere.com](andreyp.pythonanywhere.com)  
__LinkedIn:__ [linkedin.com/in/piarouski-andrei](linkedin.com/in/piarouski-andrei)  
__Git:__ [github.com/AP-Est](github.com/AP-Est)  

******
## Skills

* Python - Junior  
* Django - Junior  
* HTML + CSS - Moderate  
* Git - Moderate  
* Jira - Good  
* Confluence - Good  

******

## Languages

* English - B1
* Russian - native

********

## Employment

### SENIOR OPERATION MANAGER
__Wargaming.net — Minsk, Belarus__  
*Feb 2012 — Jul 2022*  
Responsible for the project's World of Tanks and Total War: Arena in the
direction of global support — publisher — development for CIS, APAC and
USA regions

### SYSTEM ADMINISTRATOR, SOUND ENGINEER, EXHIBITION ORGANIZER
__BelExpo — Minsk, Belarus__  
*Jun 2006 — Aug 2011*  
Maintenance of internal IT equipment/Software and equipment of
exhibitors of exhibitions, sounding of exhibitions and events, holding of
the exhibition "World of Fish"

### PROGRAMMER ENGINEER
__The National Academy of Sciences of Belarus. Institute of__
__Heat and Mass Transfer of the Likov__  
*May 2005 — Jun 2006*  
C++ development of applications (GUI and internal logic) for the Institute's
developments.

*******
## Cources

#### UDEMI / SKILLBOX / SELFEDUCATION
* Python 3 development
* Django 3
* HTML + CSS
* Git

#### WARGAMING UNIVERSITY
* Project management
* Stress management
* Time management
* Effective meeting

## Code examples 

__Python:__
```
def time_track(func):
    def surrogate(*args, **kwargs):
        started_at = time.time()

        result = func(*args, **kwargs)

        ended_at = time.time()
        elapsed = round(ended_at - started_at, 4)
        print(f'Функция работала {elapsed} секунд(ы)')
        return result
    return surrogate    
```
__JS:__
```
function validatePIN (pin) {
    let res
    var array = (""+pin).split("").map(Number) 
    for (let i = 0; i < array.length; i++) {
        if (array.length !== 4 && array.length !== 6) {
            res = false
        }
        else res = Number.isInteger(array[i])
    }
    
    return res
 }
 ```
