# Practicas-B-sicas
Código básico de utilidad
codigo Java con ciclo 
//ejercicio con ciclo for
 String texto=JOptionPane.showInputDialog("altura de la escalera?");
     int altura=Integer.parseInt(texto);
     for(int numAsterisco=1; numAsterisco<=altura; numAsterisco++){
         for(int i=0; i<numAsterisco; i++){
         System.out.print("*");
         }
         System.out.println("");
     }
