# app-DIO
{
    "versão" : " 0.2.0 " ,
    "configurações" : [
        {
            // Use o IntelliSense para descobrir quais atributos existem para depuração C #
            // Use o cursor para a descrição dos atributos existentes
            // Para mais informações, visite https://github.com/OmniSharp/omnisharp-vscode/blob/master/debugger-launchjson.md
            "name" : " .NET Core Launch (console) " ,
            "tipo" : " coreclr " ,
            "request" : " launch " ,
            "preLaunchTask" : " build " ,
            // Se você alterou as estruturas de destino, certifique-se de atualizar o caminho do programa.
            "program" : " $ {workspaceFolder} /DIO.Series/bin/Debug/netcoreapp3.1/DIO.Series.dll " ,
            "args" : [],
            "cwd" : " $ {workspaceFolder} /DIO.Series " ,
            // Para obter mais informações sobre o campo 'console', consulte https://aka.ms/VSCode-CS-LaunchJson-Console
            "console" : " internalConsole " ,
            "stopAtEntry" : falso
        },
        {
            "name" : " .NET Core Attach " ,
            "tipo" : " coreclr " ,
            "request" : " attach " ,
            "processId" : " $ {command: pickProcess} "
        }
    ]
} 
