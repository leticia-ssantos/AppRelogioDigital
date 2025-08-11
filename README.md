# Relógio Digital Android

## Descrição

Este é um aplicativo Android simples que exibe um relógio digital na tela. O objetivo principal deste projeto é demonstrar o uso do componente TextClock.

## Funcionalidades Principais

*   **Exibição do Nome do Aplicativo:** Um `TextView` (`@+id/textView`) exibe o nome do aplicativo, obtido de `R.string.app_name`.
*   **Relógio Digital em Tempo Real:** Um `TextClock` (`@+id/textClockHora`) mostra a hora atual no formato de 12 horas (hh:mm:ss).
*   **Exibição da "Hora Atual":** Um `TextView` (`@+id/textHoraAtual`) exibe o texto "HORA ATUAL: ".
*   **Captura de Hora (Botão):** Um `Button` (`@+id/btnCapturar`) com o texto "Capturar Hora". Captura a hora atual e retorna na tela. 

## Tecnologias Utilizadas

*   **Linguagem:** Java
*   **Interface do Usuário:** XML para layouts
*   **Componentes Principais do Android:**
    *   `androidx.constraintlayout.widget.ConstraintLayout` para layouts flexíveis
    *   `TextView` para exibição de texto
    *   `TextClock` para exibição de hora em tempo real
    *   `Button` para interação do usuário
*   **Bibliotecas Jetpack:**
    *   `androidx.appcompat:appcompat` para compatibilidade com versões anteriores do Android
    *   `androidx.activity:activity` para gerenciamento de atividades
    *   `androidx.core:core-ktx` para extensões Kotlin
    *   `androidx.lifecycle` para componentes sensíveis ao ciclo de vida

## Como Compilar e Executar

1.  **Clone o repositório:**
2.  **Abra no Android Studio:**
    *   Abra o Android Studio.
    *   Clique em "Open an existing Android Studio project".
    *   Navegue até o diretório onde você clonou o projeto e selecione-o.
3.  **Sincronize o projeto com os arquivos Gradle.**
4.  **Execute o aplicativo:**
    *   Selecione um emulador ou conecte um dispositivo físico.
    *   Clique no botão "Run" (ícone de play verde) no Android Studio.

## Contribuições (Opcional)

Se você encontrar bugs, melhorias ou tiver sugestões, sinta-se à vontade para abrir uma issue ou enviar uma solicitação de pull. Contribuições são sempre bem-vindas!

