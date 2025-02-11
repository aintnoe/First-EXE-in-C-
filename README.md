THE SOURCE CODE
#include <iostream>

int main (){

    std::string name;
    int age;
    std::string work;
    std::string doing;

    std::cout << "CEST QUOI TON NOM TABARNAK: ";
    std::getline(std::cin >> std::ws, name);
    
    std::cout << "Quelle age as tu?: ";
    std::cin >> age;

    std::cin.ignore();

    std::cout << "Cest quoi ton Travaille?: ";
    std::getline(std::cin >> std::ws, work);

    std::cout << "Tu fait quoi en ce moment?: ";
    std::getline(std::cin >> std::ws, doing);


    std::cout << "SALUT  " << name << '\n';
    std::cout << "WHATTT Tu as " << age << " ANS" << '\n';
    std::cout << work << " SES FOU COMME TRAVAILLE!!" << '\n';
    std::cout << doing << " Styler comme passe temp!" << '\n';

    std::cin.get();
        return 0;
}
