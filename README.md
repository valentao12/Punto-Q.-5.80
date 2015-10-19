# Punto-Q.-5.80
Further Analysis
Q.5.80 Load and run the script fi le, black_white_rose of Example 5.14.
% Script file: black _ white _ rose

clear; clf % clears variables and the figure window

T=linspace(0,2*pi,200);

subplot(1,2,1)

R=3*cos(4*T);

X=abs(R).*cos(T);

Y=abs(R).*sin(T);

fill(X,Y,’k’)

axis(‘square’)

title(‘8 petal black rose’)

subplot(1,2,2)

R1=3*sin(5*T);

X1 = (R1).*cos(T);

Y1= (R1).*sin(T);

plot(X1,Y1);

axis(‘square’)

title(‘5 petal white rose’)
