# Remove native app W10
Script para remoção de aplicativos nativos do w10

# O que faz?
- Remove aplicativos nativos do w10 atráves do **PowerShell**

## O que é necessário?
- Perfil com acesso administrador  
- Acesso ao PowerShell  

## Listando aplicativos instalados:
`Get-AppxPackage | Select-Object Name`

## Removendo aplicavo pelo nome:
`Get-AppxPackage *nomedoaplicativo* | Remove-AppxPackage`

Exemplo para remover o **skypeapp**  
`Get-AppxPackage *skypeapp* | Remove-AppxPackage`
