typedef struct lista{

    int conteudo;
    struct lista prox;
}


void inserir(list *l, int x);
{
    list *aux, *nova = malloc(sizeof(list));
    aux =l;

    nova-> conteudo = x;
    if(aux == NULL)
    {
        aux = nova;
    }
    else{
        while(aux->prox != NULL)
        {
            aux = aux->prox;
        }
        aux->prox = nova;
    }

}

void remove(list *l)
{
    list *aux;
    aux = l->prox;
    if(aux == NULL)
    {
        printf("Lista Vazia!");
    }
    else{
        l->prox = aux->prox;
        free(aux);
    }
}