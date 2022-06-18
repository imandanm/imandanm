//package com.imandanm;

import java.util.ArrayList;

public class Main {

    public static void main(String[] args) {
        ArrayList angka = new ArrayList();
        angka.add(100);
        angka.add(200);
        angka.add(1,150);
        angka.add(300);
        angka.remove(1);
        System.out.println(angka);
    }
}
