# Estrutura JSON menu desktop

```
  MenuItem[]
```

# MenuItem 
| Propriedade | Tipo | Descrição
| --- | --- | --- |
| title | string | Titulo que aparece no menu, onde o usuário passa o mouse e abrem as opções para aquele item
| href | string | Link para onde o usuário será redirecionado caso clique no item referente ao title acima
| bannerInfo | BannerInfo | Objeto que vai definir as informações do banner (Imagem, texto, url)
| itens | SubItem[] | Array contendo todos os itens do menu.

