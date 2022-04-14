# Hello_World
package com.company;

import java.util.Scanner;

public class Main {

    private static String name;

    public static void main(String[] args) {
	//

        Scanner keyboard = new Scanner(System.in);
        System.out.print("What is your name?");
        String name = keyboard.nextLine();
        System.out.println("Hello," +name + "!");


    }
}
