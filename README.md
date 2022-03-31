# Classwork
algoritmos

		/*Algoritmo 22 - Criar um algoritmo que calcule
				 *e imprima a área de um losango 
				 */
		
		double Dmaior = Double.parseDouble(JOptionPane.showInputDialog(null, "Escreva a diagonal maior."));
		double dmenor = Double.parseDouble(JOptionPane.showInputDialog(null, "Escreva a diagonal menor."));
		double area = (Dmaior*dmenor)/2;
		JOptionPane.showMessageDialog(null, "Área: "+area);
    
    
    
    /*Algoritmo 24 - Ler uma temperatura em graus centígrados e 
				 *apresentá-la convertida em graus Fahrenheit. 
				 *A fórmula de conversão está na lista1:   
				 */
				 
				 
		===========================================================================================		 

			/*Algoritmo 24 - Ler uma temperatura em graus centígrados e 
			 *apresentá-la convertida em graus Fahrenheit. 
			 *A fórmula de conversão está na lista1:   
			 */
		
		double cm = Double.parseDouble(JOptionPane.showInputDialog(null, "Converter graus Celsius para Fahrenheit. Escreva os graus centígrafos."));
		double Fahrenheit = (cm+160)/5;
		JOptionPane.showMessageDialog(null, "Resultado de F: " +Fahrenheit);
		==================================================================================================				 
				 

				 
				 
				 /*Algoritmo 25 - Calcular e apresentar o valor do volume 
				 *de uma lata de óleo, utilizando a fórmula: 
				 *volume = 3.14159 * R² *altura 
				 *
				 *	V = π · r² · h
				 *
				 */
		
		double raio, high;
		raio = Double.parseDouble(JOptionPane.showInputDialog(null, "Escreva o raio da lata."));
		high = Double.parseDouble(JOptionPane.showInputDialog(null, "Escreva a altura da lata."));
		double volume = 3.14*(raio*raio)*high;
		JOptionPane.showMessageDialog(null, "Volume da lata é "+volume);
