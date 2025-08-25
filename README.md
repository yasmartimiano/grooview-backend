# 🪩 Grooview - *Avalie. Descubra. Vibre.* 
<img src="/assets/GrooViewLogoPNG.png" alt="Logo do Grooview" width="200">

## Descrição
Grooview é uma plataforma para avaliação de músicas e álbuns, permitindo que usuários compartilhem opiniões e descubram novos conteúdos musicais. O sistema oferece funcionalidades de avaliação, comentários, criação de listas de favoritos, integração com a API do Spotify e uma timeline em tempo real, mostrando avaliações recentes feitas por outros usuários.

## Objetivo
O Grooview tem como objetivo proporcionar uma experiência organizada e interativa para os amantes de música, permitindo que descubram novos conteúdos, compartilhem suas opiniões e acompanhem a atividade da comunidade em tempo real.

## Tecnologias Usadas
- **Backend:** Java Spring Boot
- **Banco de dados:** MySQL
- **Frontend:** React
- **Outras:** HTML, TailwindCSS, JavaScript
- **Integração:** API do Spotify para autenticação de usuário e acesso a dados musicais.

## Funcionalidades
- Avaliar músicas e álbuns.
- Visualizar avaliações e comentários de outros usuários.
- Criar listas de músicas favoritas.
- Pesquisar por artistas, álbuns ou músicas.
- Sistema de login e gerenciamento de perfil de usuário, incluindo autenticação via Spotify.
- Timeline em tempo real mostrando avaliações recentes feitas pelos usuários.

## Estrutura do Projeto
- **Microserviços:** cada serviço está separado em pastas diferentes, facilitando a manutenção, escalabilidade e organização do código.
- **Backend:** contém as APIs REST, lógica de negócios e integração com o banco de dados e com a API do Spotify.
- **Frontend:** interface do usuário construída em React, consumindo as APIs do backend e integrando a API do Spotify.
- **Banco de Dados:** MySQL armazenando informações de usuários, músicas, avaliações e listas.
- **Real-time:** sistema de atualização em tempo real para a timeline de avaliações.

## Exemplo de Uso da API do Spotify
1. Usuário faz login com a conta do Spotify.
2. O sistema solicita permissão para acessar dados de músicas e playlists.
3. Usuário pode visualizar músicas, álbuns e artistas diretamente no Grooview.
4. Avaliações e listas de favoritos são sincronizadas com a experiência personalizada do usuário.
5. As avaliações feitas por qualquer usuário aparecem em tempo real na timeline.

## Como Contribuir
Para contribuir com o projeto:
1. Faça um fork deste repositório.
2. Crie uma branch com a sua feature: `git checkout -b minha-feature`.
3. Faça commit das alterações: `git commit -m "Descrição da feature"`.
4. Envie para o repositório remoto: `git push origin minha-feature`.
5. Abra um Pull Request para revisão.
