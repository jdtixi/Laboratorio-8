# UNIVERSIDAD DE LAS FUERZAS ARMADAS-ESPE
 
![](https://upload.wikimedia.org/wikipedia/commons/3/3a/Logo_ESPEOk.png)


---------------------
#  LABORATORIO 8
                                                                            
                                                                            
                                                                            
                                                                            
                                                                            
                                                                            
                                                                           
                                                                           
       Janeth Katherine Oyasa Sepa, Juan Daniel Tixi Yupa
       DEPARTAMENTO DE ELECTRICA Y ELECTRONICA
       ESPE, Autopista General Rumiñahui S/N y Ambato, Sangolquí 171103.
       E-mail: jkoyasa@espe.edu.ec, jdtixi@espe.edu.ec
       Noviembre 2020 – Abril 2021
       Fundamentos de Circuitos Eléctricos
       
       
---------------------

# 1. Objetivo General

Comprobar por medio de la práctica, la simulación y el análisis, el Teorema de Máxima Transferencia de Potencia, además, de mejorar la comprensión debido al circuito armado en el simulador para comprobar las respuestas obtenidas en los cálculos. 


---------------------

# 2. Objetivos Específicos 
       
-	Abstraer de forma sencilla y clara el conocimiento sobre cuando es importante obtener la Máxima Transferencia de Potencia.
-	Reconocer la utilidad y mejorar la comprensión sobre el Teorema de Máxima Transferencia de Potencia. 
-	Comprobar la aplicabilidad de como la potencia máxima se entrega a la carga cuando la resistencia de carga es igual a la resistencia interna de una fuente donde podemos trabajar mejor en los conceptos principales.
             
       
---------------------

# 3. Marco Teórico

Durante este parcial los temas tratados se entrelazan para mejorar la comprensión sobre los fundamentos de circuitos eléctricos, logrando que se entienda mejor el teorema de Máxima Transferencia de Potencia, donde se establece que la resistencia de carga que maximiza la transferencia de potencia es la que mantiene el valor óhmico igual a la resistencia de fuente. Especialmente ya que puede contribuir a encontrar el Teorema de Norton y Thevenin, mismos que fueron explicados en mayor profundidad en los laboratorios anteriores. Tal es el caso del tema que abordaremos en esta ocasión a lo largo de este laboratorio, el teorema de Máxima Transferencia de Potencia así nos encontramos con un circuito que armado en el simulador de Tinkercad, puede mejorar la comprensión de este tema. 

*** Teorema de Máxima Transferencia de Potencia ***

Uno de los primeros conceptos y principal que debemos abordar en este informe es el teorema de Máxima Transferencia de Potencia se puede aplicar tanto a los circuitos de CC como a los circuitos CA, con la diferencia de que la resistencia se reemplaza por la impedancia en el circuito de CA. Además, es importante recalcar que este teorema mantiene un tratamiento especial ya que hay posibles valores que puede tomar en cuestión la carga, como es el caso de energía alterna donde esta es una impedancia y con cada variación somos consientes que la aplicación varía de acuerdo con los tipos de valores. 
Uno de los personajes destacados al momento de abordar este tema es el físico e ingeniero alemán Moritz Hermann von Jacobi, a quien se le atribuye el descubrimiento de la Ley de Jacobi. También el Teorema de Máxima Potencia establece como escoger la resistencia de carga, una vez que la resistencia de fuente ha sido fijada. Incluso debemos tomar en cuenta que, dada una cierta resistencia de carga, la resistencia de potencia es siempre de valor nulo, sin depender del valor de la resistencia de carga.


*** Ejemplo del Teorema ***

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.6435-9/167201515_276468277252549_2819464727540350776_n.jpg?_nc_cat=102&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeEp10zPXdQP56FNx52J_DUgrSV90OWta9atJX3Q5a1r1jehxQ9UuJopVKx-ETDFSyZvmbLLuCgZdnYuqyJOgl6T&_nc_ohc=44HQeg9cMKMAX-A32IG&_nc_ht=scontent.fuio1-1.fna&oh=48ac09f4eef9b019cc9ea106788924cc&oe=60878B45)
 
  
 En esta ocasión vamos a tomar el siguiente circuito como ejemplo y realizamos los pasos anteriormente mencionados y de esa manera somos capaces de visualizar un posible caso de uso del teorema, sin embargo, para explicarlo de mejor manera nos centraremos sobre todo en el desarrollo que nos llevo a resolver el circuito dado en el laboratorio. 
Algo que debemos recordar es que, en una red eléctrica de CA, la potencia máxima se transferirá de la sección de fuente a la sección de carga de manera que sabemos que la impedancia de la carga es un conjugado complejo de la impedancia de la fuente. Otro aspecto fundamental para comprender este tema es que, en el circuito de CA, la fuente también posee una reactancia interna. Por lo tanto, para tener una transferencia de potencia máxima, la carga debe poseer de manera continua el mismo valor de reactancia, pero considerando además que debe ser del tipo opuesto. En otras palabras, esto significa que la carga debe tener una reactancia capacitiva equivalente para que sea aplicable al caso o si la fuente tiene reactancia inductiva, y viceversa.



![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.6435-9/167310318_276467340585976_7064591745345469516_n.jpg?_nc_cat=108&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeGehiuSvTOYd_PicIf4hmf5RRkFcZ1BLfZFGQVxnUEt9tk8xiN4GgMAlohWNTAnOuiuT-odhdcoJB9XlEbr6NoN&_nc_ohc=Yj_WMoVBpZgAX9v2BaV&_nc_ht=scontent.fuio1-1.fna&oh=004e4d6472991a7a7c832243508d85f0&oe=6087B703)
 


*** Aplicaciones del Teorema ***

Para entenderlo de mejor manera, decimos que la transferencia de potencia no coincide con la eficiencia máxima, dicho de manera más simple la aplicación de este teorema no da como resultado una eficiencia máxima o incluso alta. 
Referente a la eficiencia de este proceso se considera que es del 50% tan solo en condiciones de transferencia de potencia máxima. Así, en la red del sistema eléctrico, esta condición llega a causar una gran caída de voltaje en las líneas lo que afecta de cierta manera al proceso como tal por lo que tuvimos que considerar este aspecto al momento de realizar la práctica de este laboratorio. Sin embargo, es bueno recordar que el principal objetivo de la red del sistema de energía es el de incrementar la eficiencia en lugar de la potencia máxima. Entonces, sabemos que el sistema de energía no llego a funcionar bajo la máxima transferencia de energía.
El objetivo de la alta eficiencia en el desarrollo de este es tomado como primordial debido a la distribución de energía de CA, que nos indica una impedancia del generador relativamente baja cuando lo comparamos con la impedancia de carga. Así es fundamental comprende run caso aplicable más real, como es el caso de distribución de alimentación de CA, donde los amplificadores de audio construidos para la alta fidelidad están diseñados para una impedancia de salida relativamente baja y una impedancia de carga de altavoz que es considerada relativamente alta. Esto es mas conocido como relación, es decir, impedancia de salida e impedancia de carga conocido mejor como el factor de amortiguación que tiene un rango común de cien a mil. 


---------------------
       
# 4. Lista de componentes
![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166453232_275715357327841_3501731949848602196_n.jpg?_nc_cat=107&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeGP6_2g_eG-YPT0Gj1cymogZqKpTW_aEK1moqlNb9oQrYsbO2iW-XbLYHM9cvsmOyQcIxwLoTyQVaRPR1DLQXf6&_nc_ohc=5zU-NASdwyEAX_2gy_-&_nc_ht=scontent.fuio1-1.fna&oh=26c881dd78561b660b6d86c714282994&oe=60860A3D)

---------------------

# 5.Explicación

En la presente práctica procedemos a armar el circuito dado en la guía N°8, que es uno de los circuitos más simple que se estudian en el análisis de nuestra materia, el circuito lo armaremos en el simulador de Tinkercad, para eso vamos a tomar la fuente de 15 V y conectamos el polo positivo de la fuente a la primera terminal de la resistencia de 1.2k Ohm, para luego conectar la segunda terminal de la resistencia de 1.2k a la primera terminal de la resistencia de carga y la terminal que queda de esta resistencia la conectaremos al polo negativo de la fuente de 15 V.
 
---------------------

### Cálculos
Mida el voltaje y la corriente en la resistencia de carga para cada uno de las resistencias dadas

Aquí incluiremos el ejemplo de los 4 primeros valores de las resistencias, en el artículo hemos dejado todos los cálculos para las demás resistencias.

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/165440031_275718287327548_309379842936422743_n.jpg?_nc_cat=100&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeGHpXZmCcmrU-RUDHBvA9VhBPUUuuAZJSkE9RS64BklKQlYP1I9KmjBrVal1L7qpLxWy6up7fo4_vO-Hc_BbkiZ&_nc_ohc=J0f7QeNqAccAX_L2sJg&_nc_ht=scontent.fuio1-1.fna&oh=e5a4a80d9de692bb74bb8e5b96cfb1f7&oe=60879D93)

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.6435-9/167169881_276431163922927_3144217169566029656_n.jpg?_nc_cat=107&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeHZwU9EdFm-jacxbefgaHuwhMgvsT_GqQKEyC-xP8apAmVEVA6q92B4cbA2oWi345GNetxcngEBgGwgtqa7iQh-&_nc_ohc=Uv4_XsUFEu8AX9KuZyk&_nc_ht=scontent.fuio1-1.fna&oh=c75ad0f1010fb9cf85947bac8e24bcbe&oe=608A1B8E)

En el  simulador obtenemos:

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166392999_275715363994507_178812995217346773_n.jpg?_nc_cat=101&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeHv9FcEfwl-bWaYreyBc5Vh_F8PD2cKDk38Xw8PZwoOTZW0rmxnfGQnuWchBvm5y7BkxpLg_hAwWLDzQLpLFbFT&_nc_ohc=wb9cYla-bJEAX9Q4RJd&_nc_ht=scontent.fuio1-1.fna&oh=fa05796d1eba8b3438291c1ccfebbe46&oe=60864331)


![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166227458_275730397326337_2199224708777147769_n.jpg?_nc_cat=109&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeEK-ZSkDsgoBItJ9MJjVY6mxzfpDpB9Xi7HN-kOkH1eLgaN4F3Ap6qVwAhemMBhtKgaFHS5cYNgPAQqS6rBNrka&_nc_ohc=5pNXcYKFBcIAX8tEEmB&_nc_ht=scontent.fuio1-1.fna&oh=502f5d3de58093aab72b7e5acada7387&oe=60891DD7)

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.6435-9/164765979_276431160589594_5556110599103217407_n.jpg?_nc_cat=102&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeFAHnhJVQ7bESyBZb1E7B-hqGujkfqCHbGoa6OR-oIdsQfWxK1PX_hfveNKXEaFGpfrHo6qpEMZxKPehW2YEV_S&_nc_ohc=RBEbuWMU2V4AX92yPhh&_nc_ht=scontent.fuio1-1.fna&oh=3b61b66bf9c0786babd02bf7b9f58479&oe=6087E543)

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166580040_275715370661173_778363493443488406_n.jpg?_nc_cat=109&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeG3yTWyxnCMxlu-KGUNRkcsAfJoV7edQBcB8mhXt51AF53qbZdHzVX37PZqVbGYM91V0DkWaVIuBMkqWsZSNhME&_nc_ohc=NI2VKo9b8a4AX_e5y4x&_nc_ht=scontent.fuio1-1.fna&oh=33fd880b836ae7c56996713f4418618b&oe=6087555A)

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166950281_275718317327545_1708578734427841273_n.jpg?_nc_cat=102&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeEEtmWaBOFSjEZd4aRI21HAlRrkQfaDiu2VGuRB9oOK7XdCsbmK1w4hgo4ywtX2L_Oe0qEp5nwnWigYmI4k1CN6&_nc_ohc=3UjrgJPlb-IAX9PqqDS&_nc_ht=scontent.fuio1-1.fna&oh=1121c9f76979d0654dc56eb2d0371914&oe=60879541)

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.6435-9/167531745_276431167256260_1989772800105308711_n.jpg?_nc_cat=107&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeHIeDaMRDXMhpj6Bct0lnvVawORA8BJ-xZrA5EDwEn7Fq_zYq-YNCDowStyrkqdrHzxcD-56x6OTMBFgwptCGv1&_nc_ohc=bOypTsJe4CkAX8icyt4&_nc_ht=scontent.fuio1-1.fna&oh=c014a10b63f2e464b74126283534db38&oe=608A27AB)

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166227458_275715417327835_9010075674705831574_n.jpg?_nc_cat=101&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeHlUILpwrNd4xbPMItT_y7ie0tJk1B-C497S0mTUH4Lj43bXl_qGBGjqN9PegDtqfby_WSnPN_ZdAwrxkRvs0Eu&_nc_ohc=E0BHekiu3hwAX-UMvVu&_nc_ht=scontent.fuio1-1.fna&oh=40b299f26cae01527a4b8b243f9708da&oe=608831DF)

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166761752_275718337327543_2662463778662292598_n.jpg?_nc_cat=100&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeFUNjk5B0uGBcyy_Y3NJa6RPD-1wzETml88P7XDMROaX9qmE7t9gAofPV_HtncvKSZXVQONDQ3nsAQKyNq0fM_L&_nc_ohc=qVGS6CNP6gIAX88aoQV&_nc_ht=scontent.fuio1-1.fna&oh=38137a9fde9d9d859f90bca77da01ee9&oe=60890C38)

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.6435-9/166941622_276431183922925_4523397889420303761_n.jpg?_nc_cat=107&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeEtF96g1GewfQW_tcCaVTNfLaVs3mMrsmAtpWzeYyuyYJM99GOX13E3_TMz0MKxcrwUMHkqsKuSWFeV_5Kn0Lgu&_nc_ohc=rQG_d-I1jesAX-KkVi3&_nc_ht=scontent.fuio1-1.fna&oh=a0f33125f6c74ef2201b900fefafbc24&oe=60881160)

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166649180_275715410661169_3102522566301238733_n.jpg?_nc_cat=103&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeH3GFOQ_EBQomJBpGrPnwUdpeFt743vaDSl4W3vje9oNNa5Ctj1eSP4FU5_9PI0S6429ipanY85KGLgvTtmgoFg&_nc_ohc=kO6kMS0xkogAX_r9kMi&_nc_ht=scontent.fuio1-1.fna&oh=66c02c1321580e04c0d9fa86a2f65bd6&oe=6088F795)

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166094380_275718140660896_6196881548027079173_n.jpg?_nc_cat=101&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeFIf_S0Eo8CLcHj5Ih5vcMA7rknF4CFVFruuScXgIVUWoNOk_i4ZoDESfD5KZNAjsgY_n_4pUg570i7xtBd_MP6&_nc_ohc=nRaUUOCoASoAX8VihWe&_nc_ht=scontent.fuio1-1.fna&oh=3711d3f13ac27c1801bd9ca9b47ff103&oe=6087DD00)
![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166273245_275718167327560_4087682550783510392_n.jpg?_nc_cat=100&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeFBIieHEpT83aLxFa-cnsnRDiBfiHIyPW8OIF-IcjI9b4su8qfKAEfTZQIoDnJRa3EWhA1V4p2HbFhRyeiQ8AG3&_nc_ohc=RLM4hTBZTf0AX9WH5ba&_nc_ht=scontent.fuio1-1.fna&oh=2bab58c9d5423957b78d54b89ccb65b1&oe=6087689F)
![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166467366_275718170660893_9073457338352035402_n.jpg?_nc_cat=108&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeHo8Ary9hPAmb7bDtTcjEvKrySBGalklF-vJIEZqWSUX3kH1_v_6NOxknEqL06iFjwTSLa-TWAcGyxsEXbA7ahF&_nc_ohc=fQdV9ph20AQAX-Fumkz&_nc_ht=scontent.fuio1-1.fna&oh=cd40ffc8f4376c9f4b43f6e053f35dc1&oe=6085E230)
![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166008144_275718197327557_6407089260761638171_n.jpg?_nc_cat=111&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeECisGQzCII8iva9DzH9A5LGXtkcwDJJl0Ze2RzAMkmXU4JTR6cBzgW0YRDAE_TgV6zmKsPa3XsdU01wPpTJ0CD&_nc_ohc=PQ6TuLc1EXkAX-S58BA&_nc_ht=scontent.fuio1-1.fna&oh=9cb53544fade42171b7fbbf20fda49f3&oe=60887CC7)

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166859624_275718213994222_2652973170356002419_n.jpg?_nc_cat=101&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeG07d9l1RiuO_qN5sU7StLUZm_S7x3jm9Fmb9LvHeOb0XJQGtZkX-6O-M3f6a_VbS2ahJuzID53r4b-Q0ICXfYs&_nc_ohc=KhnOecfpt8cAX-tHQ6u&_nc_ht=scontent.fuio1-1.fna&oh=595e3e9b30e6b995c29b487528f4a74b&oe=6088E18B)
![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166289752_275718220660888_6464511626580933504_n.jpg?_nc_cat=101&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeEjAGtE83AN4-OoAcbkseiKP3pIU7JH1J0_ekhTskfUnVOdZ3Lg8rT465h_L1OQvYvQFylD-CoalHRfFV5Jtoj-&_nc_ohc=dYuWi66317kAX9HC6pk&_nc_ht=scontent.fuio1-1.fna&oh=d1c7241733f4a2767d8deb6bf37acddd&oe=608642FB)

Una vez hallados los valores, tantos experimentales como calculados aplicando las leyes, obtenemos la siguiente tabla

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166392999_275715537327823_6831189126268515912_n.jpg?_nc_cat=109&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeEtpn9643G1ZBuGq1QbpKVcjArCmkRtMpWMCsKaRG0ylTp8pvGsehmnzVzmKMD_0bO79ecWmCOxEDZ5eISCR_ii&_nc_ohc=m5dZ7oXjtn8AX9DuSbr&_nc_ht=scontent.fuio1-1.fna&oh=60533968815cd6a06642e503f51b7900&oe=6086BA3A)

La columna Potencia calculada experimentalmente fue obtenida usando la facilidad de las hojas de cálculo de Excel según la fórmula:

P= CELDA CORRIENTE*CELDA VOLTAJE*0.001

Ejemplo

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166976998_275715557327821_3088802971688191287_n.jpg?_nc_cat=110&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeFVag60DnkgxNFXQquB6_DnTGbO7xHduWtMZs7vEd25a9UztMGxKJXb-R0aQ_uifk8VUIilNkFhiOQGiUpYU12c&_nc_ohc=wfawVq2CEZMAX-LLVzh&_nc_ht=scontent.fuio1-1.fna&oh=bd271e335c2c939a5bd1d75b499eaccd&oe=60895E35)

y la Potencia calculada teóricamente es el resultado de multiplicar cada corriente que pasa por el resistor de carga por el voltaje en el resistor de carga.

---------------------

#### Preguntas

**¿Se cumple el Teorema de la Máxima Transferencia de Potencia?**

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166801543_275715563994487_5447391977129134242_n.jpg?_nc_cat=108&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeHxPHvU10Yat64bGWPncbrvMupeceQTqPky6l5x5BOo-Sq0liXTsyWhhOPmxoCc8mfCS1Okx8lYUVHRLLfwylFO&_nc_ohc=YjyTZATbnnkAX942XJr&_nc_ht=scontent.fuio1-1.fna&oh=ea8d9fb55154284a28cd133237b089be&oe=6089290E)

En la gráfica podemos observar como obtenemos una potencia máxima a medida que la resistencia de carga va tomando un valor casi igual que la resistencia de Thévenin, aunque no toma el mismo valor.


**¿Cuál fue la potencia máxima en RL? **

En la resistencia de 1k Ohm alcanzo una potencia de 0.0465 Watts

**¿Para qué valor de RL se obtiene la MTP? **

Con una resistencia de 1.2k Ohm  según la teoría.

---------------------

# 6. Descripción de prerrequisitos y configuración

Como primer prerrequisito para esta práctica es tener un conocimiento previo de la Potencia Máxima a manera de introducción, además de saber los teoremas de Thévenin y Norton.

El circuito no necesita de alguna configuración en especial, solo debemos asegurarnos de realizar las conexiones en serie de las resistencias correctamente. Para las fuentes de voltaje asegurarnos de que tengan lo valores adecuados de voltaje y par los multímetros, cambiar las perillas de corriente a voltaje con cuidado.

---------------------

# 7.  Aportaciones o Recomendaciones

•	La máxima transferencia de potencia es de gran importancia en el ámbito de la electrónica, ya que de acurdo a estos se diseñan transformadores, con el fin de evitar excesivas pérdidas de calor.

•	Se recomienda no olvidarse de cambiar las perillas correctamente de los multímetros, caso contrario se pueden tener valores incorrectos (ya que estamos trabajando en un simulador), en la realidad podriamos dañar el multímetro

---------------------

# 8. Conclusiones 

Al culminar la práctica N°8 de este semestre podemos visualizar no solo prácticamente, teóricamente sino matemáticamente la funcionalidad del Teorema Máximo de Transferencia de Potencia, donde se nos dice que en una red suministra una potencia máxima a una resistencia de carga RL, cuando el valor de dicha resistencia de carga  es equivalente a la resistencia equivalente de Thévenin de la red, recordando que lo que nos permite Thévenin que el valor de las resistencias se puede sustituir por otra fuente de tensión y así facilitar los cálculos en la resolución del circuito. 
Si algo podemos resaltar de este laboratorio es que este teorema nos permitió conocer de mejor manera el calculo de la máxima potencia no solo con cálculos manuales descritos en el informe, sino que además con ayuda del uso del simulador Tinkercad, que para esta ocasión resulto ser mucho más didáctico para analizar los resultados tabulados en las tablas anteriormente presentadas, donde de manera más general podemos comprobar la eficacia de este método que describe la condición para la transferencia de potencia máxima de una red activa a una resistencia de carga externa.

Además, analizando los resultados expuestos en el informe somos capaces de visualizar que el porcentaje de error presente en el laboratorio no es grande, de modo, que concluimos que los resultados obtenidos y plasmados en este informe son en su mayoría exitosos hay que lo único diferenciable es el uso de decimales, donde en el simulador se mantienen los valores en decimas y nosotros por preferencia para mayor exactitud decidimos ponerlos en milésimas.  



---------------------

# 9. Bibliografía


---------------------

# 10. Anexos

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166094380_275718140660896_6196881548027079173_n.jpg?_nc_cat=101&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeFIf_S0Eo8CLcHj5Ih5vcMA7rknF4CFVFruuScXgIVUWoNOk_i4ZoDESfD5KZNAjsgY_n_4pUg570i7xtBd_MP6&_nc_ohc=nRaUUOCoASoAX8VihWe&_nc_ht=scontent.fuio1-1.fna&oh=3711d3f13ac27c1801bd9ca9b47ff103&oe=6087DD00)
![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166273245_275718167327560_4087682550783510392_n.jpg?_nc_cat=100&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeFBIieHEpT83aLxFa-cnsnRDiBfiHIyPW8OIF-IcjI9b4su8qfKAEfTZQIoDnJRa3EWhA1V4p2HbFhRyeiQ8AG3&_nc_ohc=RLM4hTBZTf0AX9WH5ba&_nc_ht=scontent.fuio1-1.fna&oh=2bab58c9d5423957b78d54b89ccb65b1&oe=6087689F)
![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166467366_275718170660893_9073457338352035402_n.jpg?_nc_cat=108&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeHo8Ary9hPAmb7bDtTcjEvKrySBGalklF-vJIEZqWSUX3kH1_v_6NOxknEqL06iFjwTSLa-TWAcGyxsEXbA7ahF&_nc_ohc=fQdV9ph20AQAX-Fumkz&_nc_ht=scontent.fuio1-1.fna&oh=cd40ffc8f4376c9f4b43f6e053f35dc1&oe=6085E230)
![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166008144_275718197327557_6407089260761638171_n.jpg?_nc_cat=111&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeECisGQzCII8iva9DzH9A5LGXtkcwDJJl0Ze2RzAMkmXU4JTR6cBzgW0YRDAE_TgV6zmKsPa3XsdU01wPpTJ0CD&_nc_ohc=PQ6TuLc1EXkAX-S58BA&_nc_ht=scontent.fuio1-1.fna&oh=9cb53544fade42171b7fbbf20fda49f3&oe=60887CC7)

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166859624_275718213994222_2652973170356002419_n.jpg?_nc_cat=101&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeG07d9l1RiuO_qN5sU7StLUZm_S7x3jm9Fmb9LvHeOb0XJQGtZkX-6O-M3f6a_VbS2ahJuzID53r4b-Q0ICXfYs&_nc_ohc=KhnOecfpt8cAX-tHQ6u&_nc_ht=scontent.fuio1-1.fna&oh=595e3e9b30e6b995c29b487528f4a74b&oe=6088E18B)
![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166289752_275718220660888_6464511626580933504_n.jpg?_nc_cat=101&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeEjAGtE83AN4-OoAcbkseiKP3pIU7JH1J0_ekhTskfUnVOdZ3Lg8rT465h_L1OQvYvQFylD-CoalHRfFV5Jtoj-&_nc_ohc=dYuWi66317kAX9HC6pk&_nc_ht=scontent.fuio1-1.fna&oh=d1c7241733f4a2767d8deb6bf37acddd&oe=608642FB)

![](https://scontent.fuio1-1.fna.fbcdn.net/v/t1.0-9/166432343_275708847328492_3559868961322970915_o.jpg?_nc_cat=107&ccb=1-3&_nc_sid=8bfeb9&_nc_eui2=AeH4vL7d-XTElFQlv7jM9Igcc8bXaE3BvyxzxtdoTcG_LMPS65TLsNIbigPSJcN5epq4U8qaN-KQ1LijY0slRN6x&_nc_ohc=cyosk9Sp0VAAX-4MYKR&_nc_ht=scontent.fuio1-1.fna&oh=f9d6d283a233ec74b9d70bcfb64137fc&oe=6088B9BB)
