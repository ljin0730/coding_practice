# coding_practice-densties_Pb208

#importing the required module
import matplotlib.pyplot as plt

#x axis values
x = [0.859189E-01,0.860841E-01,0.862981e-1]
#corresponding y axis values
y = [0.718235E-01,0.716325e-01,0.713786E-1]

#plotting the points
plt.plot(x,y)

#naming the x axis
plt.xlabel('r [fm] rho_n [fm^{-3}]')

#naming the y axis
plt.ylabel('rho_p {fm^{-3}]')

#giving a title to my graph
plot.title('Pb208_DD-ME1')

#function to show the plot
plot.show()
