Celem projektu jest odtworzenie sterowania dla quadrotora na podstawie artykułu:📄 https://arxiv.org/html/2403.17551v2 wykorzystaniem metody MPCC++ oraz jej implementacja w symulacji.

## Założenia projektu

📖 Analiza artykułu

🧱 Stworzenie prostej symulacji quadrotora (model jako prostopadłościan + 4 siły)

🐍 Zaimplementowanie algorytmu sterowania w Pythonie

🎯 Strojenie sterownika metodą TuRBO

🧪 Testy w środowisku symulacyjnym

🚁 Ewentualne sprawdzenie działania na rzeczywistym dronie (jeśli będzie taka możliwość)

## Do przemyślenia

Czy do symulacji użyć Gazebo i sterować siłami poprzez ROS?

W jaki sposób zaimplementować sterowanie i strojenie w architekturze ROS/Python?

Potrzeba dokładnego odwzorowania modelu dynamiki quadrotora – czy wystarczy uproszczony model?

## Wymagania

Python 3.10+

ROS 2 (opcjonalnie, jeśli wybierzemy Gazebo)

Gazebo (lub alternatywa, np. PyBullet, jeśli zależy nam na prostszej integracji)

biblioteki: numpy, scipy, (i jeszcze inne)
