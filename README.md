<h1>Usando o AWS CDK</h1>

<p><a href="https://docs.aws.amazon.com/pt_br/cdk/v2/guide/ecs_example.html">Documentacao AWS com exemplo deste estudo.</a></p>
<ul>
<li><strong>aws --version</strong> verificar a versao do cli da aws instalada;</li>
<li><strong>aws configure</strong> configurar a credencial para conseguir fazer o deploy;</li>
<li><strong>cdk --version</strong> verificar a versao do CDK;</li>
</ul>

<h2>Criar projeto CDK com JAVA</h2>
<ul>
<li><strong>cdk init app --language java</strong> cria projeto CDK com Java;</li>
<li><strong>cdk bootstrap aws://idUsuario/regiao</strong> define uma regiao;</li>
<li><strong>cdk list</strong> identifica as stack do projeto;</li>
<li><strong>cdk deploy </strong> faz o deploy das stack na AWS pode-se usar o nome da stack ou o argumento --all para deploiar todas as stacks;</li>
</ul>
