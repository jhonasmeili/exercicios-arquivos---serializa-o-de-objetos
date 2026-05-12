/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 */
package Arquivos.Exercicios.Ex01;

import java.io.BufferedReader;
import java.io.BufferedWriter;
import java.io.FileReader;
import java.io.FileWriter;
import java.util.Scanner;

/**
 *
 * @author aluno
 */

//Exercícios 1 e 2

public class main {
    public static void main(String[] args) throws Exception{
        BufferedWriter bw = new BufferedWriter(
            new FileWriter("Exercicio1-arq.txt")
        );
        int index = 0;
        do{
            Scanner s = new Scanner(System.in);
        
            System.out.printf("Digite um nome: "); 
            
            
            if(s.hasNextInt()){
                int opt = s.nextInt();
                if(opt == 0){
                    index = 1;
                }
            } else {
                String str = s.nextLine();
                bw.write(str);
                bw.newLine();
            }
            
        } while(index == 0);
        bw.close();
        
        BufferedReader br = new BufferedReader(
            new FileReader("Exercicio1-arq.txt")
        );
            
        String linha;
        int linhas = 0;
        while((linha = br.readLine()) != null){
            linhas++;
        }
        System.out.printf("%d linhas registradas.\n", linhas);
        br.close();
    }
}
