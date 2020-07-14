<h2>Wind Power Prediction</h2>
<strong>Category: IBM Cloud Application</strong>

Project Description:
<p>With the increase in the population of the world, its demand for the energy supply is hiking day by day. To match the demand for the energy supply, people are relying more on renewable energies. By the year 2030, the energy demand will be twice as of now. Wind energy plays a significant role in energy contribution to the world.
The energy output of a wind farm is highly dependent on the wind speed, that the area is having other factors like rotor radius, hub height, and air density. Predicting the energy output of the wind farm is highly based on the instantaneous wind speed forecasting.
In this project, we'll be using the combination of a decision tree with the ANN model. Our model will be able to find the patterns and the co-dependence of the factor like Air temperature, pressure, humidity, and wind flow direction through which we'll be able to predict instantaneous wind speed with higher precision. Further, this project will also have a real-time web-based dashboard through, which a valid user can easily understand the energy output forecasting from their wind farm. This project will be able to predict the energy output of a small, medium, and large-sized wind farm.
This live application will allow any authentic user to get the information for the installation of either one turbine or up to several turbines over a large scale. Wind speed and its other factors provide a non-linear output, but over here with the help of newly developed algorithms we provide a linear relationship with the input variables and output results. As well as more user-friendly output to depict the prediction obtained from RBF-ANN based algorithm. To overcome the issue of heavy training and not easily modifying the dataset (which varies scale to regions) we come up to split and sample the data with the help of the Decision tree algorithm. Hence, our model will be working on a combined algorithm of CART & (RBF)ANN. With this algorithm, we aim to minimize the cons of each independent techniques and to get a well-optimized algorithm also a very flexible model. Our model will have some corner cases which help in the fault detection process which directly reduces the cost from Maintenance & operating area.</p>
Mathematical Model:
<br>
The power output by a wind turbine
<br>
<p>Pk=Cp*(1÷2)*π*rho*(d<sup>2</sup>÷4)u<sup>3</sup></p>
· rho is the air density
<br>
· CP is the power coefficient
<br>
· PK is power captured
<br>
· d is the diameter of the rotor disc
<br>
· u is instantaneous win speed
<br>
(The best theoretical performance of a turbine is the Betz limit, at which cp =16/27)
<p>Air Density is a function of Temperature and Air pressure and hence, considering these two factors is as important as others.
Wind direction, turbulence and shear stress are other important factors which help in the better tuning of the model
Turbulence Intensity is given by:
                                            Ti = sigma(u(t))/U,

where sigma(u(t)) is the standard deviation of the wind speed during a 10 min interval.
We will analyze more important dependent factors for the better prediction of the power output.<p>

Here is our end result : https://node-red-fimuh.eu-gb.mybluemix.net/ui/#!/0?socketid=ebKSWFoSjBWlnyORAAAS
