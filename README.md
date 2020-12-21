# Covid-19 Greece

### **This is a visual representation of the pandemic in Greece.**<br/>
Data have been hardcoded on the script and they are available on the daily covid-19 records,<br/>
shared by Hellenic National Public Health Organization [(EODY)](https://eody.gov.gr/) and they can be found [here](https://eody.gov.gr/epidimiologika-statistika-dedomena/ektheseis-covid-19/).

#
Data are saved into lists starting from 1st November till 20 December, while the User has the option<br/> 
to adjust their starting point **(the "from" part)**.

User also has the option to "utilize" an adjustment regarding the weekends *(Saturday and Sunday)* in<br/>
order to get a finer percentage graph since percentages do NOT seem to be able to generalize for the<br/> 
whole population, due to the fact that Tests drop significantly at the weekends. 

:heavy_check_mark: adjustment = 
```diff 
+ True 
```
![Image](/images/Percentage_graph.jpg)

:x: adjustment =
```diff 
- False 
```
![Image](/images/Percentage_graph.jpg)

The next three graphs represent: 
- **Tests that were made by EODY** *(without counting the rapid tests)* 
- **People died due to coronavirus**
- **Intubated patients**

![Image](/images/Tests.jpg)
![Image](/images/Deaths.jpg)
![Image](/images/Intubated_patients.jpg)
#
