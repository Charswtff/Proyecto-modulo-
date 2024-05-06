#include <iostream>
using namespace std;

void preguntasGrooming() {
    int pregunta;
    do {
        cout << "1.- ¿Que es el grooming y como puedo identificar si soy victima de ello?" << endl;
        cout << "2.- ¿Cuales son las señales de advertencia de que alguien está intentando hacerme phishing" << endl;
        cout << "3.- ¿Como puedo protegerme contra el phishing en linea?" << endl;
        cout << "4.- ¿Que es el stalkeo en linea y cuales son sus riesgos?" << endl;
        cout << "4.- ¿Que es el stalkeo en linea y cuales son sus riesgos?" << endl;
        cout << "5.- ¿Cuales son las medidas de seguridad que debo tomar para evitar ser victima de stalkeo?" << endl;
        cout << "6.- ¿Que puedo hacer si sospecho que alguien esta stalkeandome en linea?" << endl;
        cout << "7.- ¿Cual es la diferencia entre el grooming y el stalkeo en linea?" << endl;
        cout << "8.- ¿Que informacion personal debo evitar compartir en linea para protegerme del grooming y el stalkeo?" << endl;
        cout << "9.- ¿Como puedo detectar si alguien esta tratando de manipularme a traves del grooming?" << endl;
        cout << "10.- ¿Que puedo hacer si creo que he sido victima de grooming o stalkeo en linea?" << endl;
        cout << "11.- Regresar al menu principal" << endl;
        cout << "Seleccione su opcion: ";
        cin >> pregunta;

        switch (pregunta) {
            case 1:
                
                break;
            case 2:
                
                break;
            
            case 11:
                return; 
            default:
                cout << "Opcion invalida. Por favor, seleccione una opcion valida." << endl;
                break;
        }
    } while (pregunta != 11);
}

void miniTutorialQr() {
    cout << "Se mostraran los pasos para crear un codigo QR" << endl;
    cout << "1.- Ingrese a una pagina web en el explorador de su preferencia" << endl;
    cout << "2.- Ingrese el enlace de la pagina donde se escaneara el codigo" << endl;
    cout << "3.- Escoger los colores y el tamaño" << endl;
    cout << "4.- Verificar si funciona en todos los dispositivos" << endl;
}

int main() {
    int opcion;
    do {
        cout << "\nMenu" << endl;
        cout << "1.- Zona de preguntas" << endl;
        cout << "2.- Mini Tutorial: Como crear un codigo QR" << endl;
        cout << "3.- Salir del programa" << endl;
        cout << "Seleccione su opcion: ";
        cin >> opcion;

        switch (opcion) {
            case 1:
                preguntasGrooming();
                break;
            case 2:
                miniTutorialQr();
                break;
            case 3:
                cout << "Saliendo del programa..." << endl;
                break;
            default:
                cout << "Opcion invalida. Por favor, seleccione una opcion valida." << endl;
                break;
        }
    } while (opcion != 3);

    return 0;
}
