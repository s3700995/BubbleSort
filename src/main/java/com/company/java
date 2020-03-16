package com.company;

public class Main {

    static int[] A = {-1, 61, -3, 83, 38};

    public static void main(String[] args) {

        System.out.println("Hello World!");
        bubbleSort();

    }

    public static void bubbleSort() {

        int n = A.length;

        for (int i = 0; i < n - 1; i++) {
            for (int j = 0; j < n-i-1; j++) {
                if (A[j] > A[j + 1]) {
                    swap(A[j], A[j + 1], j);

                }
            }
        }

        for (int a = 0; a < n; a++) {
            System.out.println(A[a]);
        }

    }

    static void swap(int a, int b, int i) {
        int temp;
        temp = a;
        a = b;
        b = temp;

        A[i] = a;
        A[i+1] = b;
    }

}
