﻿## EXERCICIO
## exercicio 1
  public static void somaVetores() {

        int[] vetor1 = new int[]{1, 2, 3, 4, 5};
        int[] vetor2 = new int[]{1, 1, 1, 1, 1};
        int[] vetorR = new int[5];

        for (int i = 0; i < vetorR.length; i++) {
            vetorR[i] = vetor1[i] + vetor2[i];
            System.out.println(vetorR[i]);
        }
    }

    public static void main(String[] args) {
        somaVetores();;
    }
}

## exercicio 2
public static void maior(){

    int [] vetor1 = new int [] {3,5,4,2,1};
    
    int n; 
    n = vetor1[0];
    for (int i = 0; i < 5; i++){
        
        if (n < vetor1[i]){
            n = vetor1[i];
        }
    }
    System.out.println("Maior elemento = " + n);
}

    public static void main(String[] args) {
        maior();
    }
    
}

## exercicio 3
public static void media() {

        int[] vetor1 = new int[]{15, 20, 25, 30, 35};
        int somatorio = 0;
        int media;

        for (int i = 0; i < vetor1.length; i++) {
            somatorio += vetor1[i];
            System.out.println(somatorio);
        }

        media = somatorio / vetor1.length;
        System.out.println(media);
    }

    public static void main(String args[]) {
        media();
    }
}

## exercicio 4
  public static void copia() {

        int[] vetor1 = new int[]{1, 2, 3, 4, 5};
        int[] vetor2 = new int[5];

        for (int i = 0; i < vetor2.length; i++) {
            vetor2[i] = vetor1[i];
      System.out.println(" --vetor1 = " + vetor1[i]);;
            System.out.println(" --vetor2 = " + vetor2[i]);;

        }

    }

    public static void main(String[] args) {
        copia();
    }

}

## exercicio 5
    public static void igualdade () {
        
        int [] vetor1 = new int []{1,2,3,4,5};
        int [] vetor2 = new int []{1,2,3,4,5};
        boolean resultado = false;

        for (int i = 0; i < vetor1.length; i++) {        
          if (vetor1[i] == vetor2[i]){
            resultado = true;
          }
          else if (vetor1 [i] != vetor2 [i]){
              resultado = false;
          }
          System.out.println(resultado);
        }
    }
    
        public static void main (String args[]) {
            igualdade ();
        }
    }

## exercicio 6
  public static void inverter(int[] vetor) {

        int n = vetor.length;
        for (int i = 0; i < n / 2; i++) {
            int temp = vetor[i];
            vetor[i] = vetor[n - i - 1];
            vetor[n - i - 1] = temp;
        }
    }

    public static void main(String[] args) {
        int[] vetor = {1, 2, 3, 4, 5, 6, 7};
        System.out.println("Vetor original: " + Arrays.toString(vetor));
        
        inverter(vetor);
        
        System.out.println("Vetor invertido: " + Arrays.toString(vetor));
    }
}

## exercicio 7
public static void parImpar(){

        int[] vetor = new int[]{6, 3, 8, 10,7,8,5};
        
        for (int i = 0; i < vetor.length; i++) {
            if (vetor[i] % 2 == 0) {
                System.out.println("sao pares: " + vetor[i]);
            } else {
                System.out.println("sao impares: " + vetor[i]);
            }

        }
    }

    public static void main(String[] args) {
        
        parImpar();
      
    }

## exercicio 8
 public static void limpar(){

        int[] vetor = new int[]{1, 2, 3, 4, 5};
        int[] limparV = new int[]{0};
        for (int i = 0; i < vetor.length; i++) {
            vetor = limparV;
            System.out.println(Arrays.toString(vetor));
        }
    }
    
    public static void main(String[] args) {
        limpar();
    }
    
## exercicio 9
 public static void crescente() {

        int[] vetor = new int[]{1, 2,3,4,5};
        Arrays.sort(vetor);

        for (int i = 0; i < vetor.length; i++) {
            System.out.println("ordem: " + Arrays.toString(vetor));
        }
    }


    public static void main(String[] args) {
        
        crescente();  
    }   
    }

## exercicio 10
  public static void achar(){
    
        int[] vetor = new int[]{1,2,3,4,5,6,7};
        
        int numero = 4;
        int posicao = Arrays.binarySearch(vetor, numero);
        int local = vetor[posicao];
        
        for( int i = 0 ; i <= vetor.length ; i++){
            System.out.println("Local é " + local + " indice escolhida " + posicao);
        }
    }

    public static void main(String[] args) {
        
        achar();{
        
    }
