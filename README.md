1.Criar um repositório GitHub e clonar localmente.
Feito
2. Executar os testes com pytest e corrigir o erro na aplicação.
Corrigi a aplicação. Mas não fiz os testes
3. Fazer commits semânticos para cada alteração.
Não fiz para cada alteração pois esqueci no desespero. Então enviei grandes comist
4. Criar um workflow GitHub Actions que:
○ Execute os testes com pytest.
○ Crie uma imagem Docker e publique no DockerHub.
não consegui fazer essa parte
5. Criar configuração de Deployment e Service no Kubernetes, usando Kustomize.
Feito
6. Ajustar o workflow de CI/CD para:
○ Atualizar o kustomization.yaml com a imagem gerada e versão.
○ Fazer commit e push automático da alteração.
Se a imagem funcionnace iria funcionar a configuração

7. Configurar um cluster local com Kind, com 3 nodes (sendo um control-plane).
Feito nome bsi-devops

Não consegui fazer daqui para baixo    
9. Instalar e configurar o ArgoCD.
10. Criar um App no ArgoCD apontando para seu repositório e diretório de
configurações Kubernetes.
11. Fazer a sincronização via ArgoCD e testar a aplicação com kubectl
port-forward.
12. Fazer uma alteração no FastAPI, realizar o push e verificar se o ArgoCD detecta e
sincroniza corretamente.
