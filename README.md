# ArbolBinario
Arbol binario numero
package com.mycompany.algoritmia;

/**
 *
 * @author a2211
 */
public class Algoritmia {

    public static void main(String[] argumentos) {
        Arbol arbol = new Arbol();
        arbol.insertar(1);
        arbol.insertar(3);
        arbol.insertar(5);
        arbol.insertar(9);
        arbol.insertar(2);
        System.out.println("Recorriendo inorden:");
        arbol.inorden();
        System.out.println("Recorriendo postorden:");
        arbol.postorden();
        System.out.println("Recorriendo preorden:");
        arbol.preorden();
        System.out.println(arbol.existe(1));
        System.out.println(arbol.existe(4));
        System.out.println(arbol.existe(2));
    }
}
