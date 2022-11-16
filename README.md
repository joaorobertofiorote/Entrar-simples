entrada = input("[E]ntrada" "[S]air:")
senha = input("Senha: ")
senhacert = '12345678'
if (entrada == 'E' or entrada == 'e') and senha == senhacert:
    print('entrar')
else:
     print('sair')
