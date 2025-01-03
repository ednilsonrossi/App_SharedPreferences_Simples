# SharedPreferences_Simples

Aplicativo consiste em um exemplo simples do uso do SharedPreferences para armazenar data e hora da ultima vez que o aplicativo passa pelo estado de _stopped_. Nesse aplicativo ao carregar a aplicação no onResume() a interface é atualiada com os dados que estão no sharedpreferences. Ao passao pelo onStop() o LocalDateTime é armazenado no arquivo.
