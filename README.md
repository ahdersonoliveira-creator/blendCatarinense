# Gerador de Blends - Sistema de Autenticação

Sistema completo de geração de blends de cinzas para a Carbonífera Catarinense, com autenticação de usuários, cálculos automáticos e histórico de lotes.

## 🚀 Funcionalidades

- **Sistema de Autenticação**: Login e cadastro de usuários com diferentes níveis de permissão (Admin e Usuário)
- **Gerenciamento de Materiais**: Cadastro e edição de materiais com suas propriedades (PCS, cinzas, umidade, enxofre, estoque, custos)
- **Cálculo de Blends**: Cálculo automático de proporções para atingir especificações técnicas
- **Auto Blend**: Geração automática de blends otimizados
- **Histórico de Lotes**: Salvamento e carregamento de lotes anteriores com **exclusão individual**
- **Exportação**: Geração de PDF e Ordem de Carregamento (OC)
- **Temas**: Suporte para tema claro e escuro
- **Responsivo**: Interface adaptada para desktop e mobile

## 📋 Novidades desta Versão

✅ **Botão de exclusão individual por histórico**: Agora cada item do histórico possui seu próprio botão de exclusão, permitindo remover lotes específicos sem precisar excluir todo o histórico.

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3 (com variáveis CSS para temas)
- JavaScript (Vanilla)
- html2pdf.js (para geração de PDFs)
- LocalStorage (para persistência de dados)

## 📦 Como Usar

### Opção 1: Hospedagem no GitHub Pages

1. Faça fork ou clone este repositório
2. Vá em **Settings** > **Pages**
3. Em **Source**, selecione a branch `main` e a pasta `/ (root)`
4. Clique em **Save**
5. Aguarde alguns minutos e acesse o link fornecido pelo GitHub Pages

### Opção 2: Uso Local

1. Baixe o arquivo `index.html`
2. Abra o arquivo diretamente no navegador (duplo clique)
3. O sistema funcionará completamente offline

## 👥 Usuários Padrão

O sistema vem com um usuário administrador padrão:

- **Usuário**: admin
- **Senha**: admin123

⚠️ **Importante**: Altere a senha do administrador após o primeiro acesso!

## 🔐 Níveis de Permissão

### Administrador
- Acesso completo ao sistema
- Gerenciamento de usuários
- Edição de materiais
- Cálculo automático de PCS e Enxofre
- Exportação de dados

### Usuário
- Criação e cálculo de blends
- Visualização de histórico
- Exportação de relatórios
- Sem acesso ao gerenciamento de usuários

## 📱 Recursos Mobile

- Interface responsiva
- Suporte a PWA (Progressive Web App)
- Instalável na tela inicial
- Funciona offline após primeira carga

## 🔄 Sincronização entre Dispositivos

O sistema permite sincronizar usuários entre diferentes dispositivos através de:

1. **Código de Sincronização**: Gere um código na tela de usuários e compartilhe
2. **Exportação/Importação**: Exporte a lista de usuários em JSON e importe em outro dispositivo

## 📊 Estrutura de Dados

Os dados são salvos localmente no navegador usando LocalStorage:

- `blendMaterials`: Lista de materiais cadastrados
- `blendPercentages`: Percentuais atuais dos materiais
- `blendHistory`: Histórico de lotes gerados
- `blendUsers`: Lista de usuários cadastrados
- `blendTheme`: Tema selecionado (light/black)

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abrir um Pull Request

## 📄 Licença

Este projeto é de uso interno da Carbonífera Catarinense.

## 📞 Suporte

Para dúvidas ou suporte, entre em contato com o departamento de TI.

---

**Desenvolvido para Carbonífera Catarinense** 🏭
