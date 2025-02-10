#include <iostream>
using namespace std;

void criaMatriz(int n, int matriz[][100]) {
    for (int i = 0; i < n; i++) {
        for (int j = 0; j < n; j++) {
            cout << "Digite o elemento [" << i << "][" << j << "] da matriz: ";
            cin >> matriz[i][j];
        }
    }
}

void printMatriz(int n, int matriz[][100]) {
    for (int i = 0; i < n; i++) {
        for (int j = 0; j < n; j++) {
            cout << matriz[i][j] << " ";
        }
        cout << endl;
    }
}

void multMatriz(int n, int matriz1[][100], int matriz2[][100], int matrizMult[][100]) {
    for (int i = 0; i < n; i++) {
        for (int j = 0; j < n; j++) {
            matrizMult[i][j] = matriz1[i][j] * matriz2[i][j];
        }
    }
}

int main() {
    int n;

    // Tamanho da matriz quadrada
    cout << "Digite o tamanho das matrizes quadradas: ";
    cin >> n;
    cout << endl;

    // Matrizes com tamanho máximo 100x100
    int matriz1[100][100], matriz2[100][100], matrizMult[100][100];

    // Preenchendo as matrizes
    cout << "Preencha a matriz 1:" << endl;
    criaMatriz(n, matriz1);
    cout << endl;

    cout << "Preencha a matriz 2:" << endl;
    criaMatriz(n, matriz2);
    cout << endl;

    // Multiplicando as matrizes
    multMatriz(n, matriz1, matriz2, matrizMult);

    // Exibindo a multiplicação
    cout << "Matriz resultante da multiplicacao:" << endl;
    printMatriz(n, matrizMult);

    return 0;
}
