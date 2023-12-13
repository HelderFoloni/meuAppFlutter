# meuAppFlutter
import 'dart:io';

void main (){
  print('Digite 1 para acenar you qualquer outra tecla para sair: ');
  int numero = int.parse(stdin.readLineSync()!);
    if(numero != 1) {
      print('você saiu');
    } else {
      print('Hello world');
    }
}
