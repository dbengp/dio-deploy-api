# dio-deploy-api
no momento, não possuo subscription válida para implantar em um webapp do Azure. Mas esses passos podem ser seguidos considerando um codigo rodando no Visual Studio Code:

1. Pressione F1;
  
2. Cole isso "Azure App Service: Create New Web App (Advanced)".

3. Se solicitado, entre na sua conta do Azure.

4. Selecione uma subscription válida.

5. Selecione "Create new Web App... Advanced".

6. Dê um nome ao WebApp.

7. Crie um grupo de recursos (para tudo no Azure terá que ser criado pelo menos 1).

8. Para runtime stack, selecione .NET8(LTS).
 
9. Dê preferência a zonas proxima a sua aplicão.

10. Crie um "App Service plan", com o respectivo Pricing Tier.

11. Por fim, selecione Deploy.
