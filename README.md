# Normal-Distribution

Método de Box-Muller para simular una normal estándar.
De acuerdo con Papoulis, para utilizar el método de Box_Muller se necesita considerar dos variables aleatorias independientes U_1,U_2 cada una con una distribución
uniforme en el intervalo (0,1), las cuales hacen posible la generación de valores u_1,u_2, pertenecientes a las variables ya mencionadas.

Para generar los valores z_1,z_2, correspondientes a las variables aleatorias independientes Z_1,Z_2, cada una con una distribución normal estándar,
se utilizan (6.4.1) y (6.4.2)

z_1=√(-2Ln(u_1))  cos⁡(2πu_2 )
z_2=√(-2Ln(u_1))  sen⁡(2πu_2 )

Por lo tanto, mediante los valores z_1  y z_2 obtenemos los valores correspondientes para poder simular una normal estándar.
