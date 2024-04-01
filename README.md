#include <iostream>

using namespace std;

int main()
{
    cout << " Nama : Valentino Silalahi " << endl;
    cout << " Nim  : 2310431015 " << endl;
    cout << " Program mengganti huruf vokal menjadi huruf 'i' " << endl;

    string teks;

    cout << endl << " Masukkan lirik lagu : ";
    getline ( cin,teks ) ;

    while(true) {
    for ( char & vokal : teks )
    {
        if ( vokal == 'A' || vokal == 'a' ) {vokal = 'i'; }
        if ( vokal == 'U' || vokal == 'u' ) {vokal = 'i'; }
        if ( vokal == 'E' || vokal == 'e' ) {vokal = 'i'; }
        if ( vokal == 'O' || vokal == 'o' ) {vokal = 'i'; }
    }
    cout << endl << " Output : " << teks << endl;
    break;
    }
}
