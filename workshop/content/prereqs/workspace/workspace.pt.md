---
title: "Criar um Workspace"
chapter: false
weight: 14
---

{{% notice warning %}}
O workspace Cloud9 deve ser provisionado por um usuário IAM com privilégios de administrador,
não uma conta root. Por favor, garanta que está logado como um usuário IAM e não com o usuário root.
{{% /notice %}}

{{% notice tip %}}
Extensões de navegador do tipo: Ad blockers, javascript disablers e tracking blockers devem ser desabilitados para o domínio Cloud9 ou o seu uso pode ser impactado.
Cloud9 utiliza cookies de terceiros. Você pode verificar a lista de [domínios específicos](https://docs.aws.amazon.com/pt_br/cloud9/latest/user-guide/troubleshooting.html#troubleshooting-env-loading).
{{% /notice %}}

### Use o Cloud9 na região mais próxima:
{{< tabs name="Region" >}}
{{{< tab name="N. Virginia" include="us-east-1" />}}
{{{< tab name="Oregon" include="us-west-2" />}}
{{{< tab name="São Paulo" include="sa-east-1" />}}
{{{< tab name="N. Califórnia" include="us-west-1" />}}
{{< /tabs >}}

- Select **Create environment**
- Name it **workshop**, click Next.
- In the Environment Settings  make sure the option "Create a new EC2 instance for environment (direct access)" is selected.
- Choose **t3.small** for instance type, take all default values and click **Next Step**
- Review the details, and click **Create environment** (this will take a few minutes)

- When the Cloud9 console is shown, customize the environment by closing the **welcome tab** and the **AWS Toolkit** tab, **lower work area**, and opening a new **terminal** tab in the main work area:
![c9before](/images/c9before.png)

- Your workspace should now look like this:
![c9after](/images/c9after.png)


{{% notice tip %}}
If you like this theme, you can choose it yourself by selecting **View / Themes / Solarized / Solarized Dark**
in the Cloud9 workspace menu.

{{% /notice %}}

