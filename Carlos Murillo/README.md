# EL MEJOR README DEL MUNDO MUNDIAL

## NOMBRE: Carlos Manuel Murillo Ibañez

## Plan de estudios: 14

## Semestre: 7

## Materias:
```
    - CVDS
    - ACSO
    - TPRO
    - FCFI
    - AUPN
```

![](https://i.pinimg.com/474x/d8/d2/74/d8d274bf1c74ff58d7bdef8aa69ac363--oakland-raiders-fake-quotes.jpg)

## Algoritmo de Kruskal
```
void KruskalMST(Graph* graph)  
{  
    int V = graph->V;  
    Edge result[V];
  
    qsort(graph->edge, graph->E, sizeof(graph->edge[0]), myComp);  
  
    subset *subsets = new subset[( V * sizeof(subset) )];  
  
    for (int v = 0; v < V; ++v)  
    {  
        subsets[v].parent = v;  
        subsets[v].rank = 0;  
    }  
    while (e < V - 1 && i < graph->E)  
    {  
        Edge next_edge = graph->edge[i++];  
  
        int x = find(subsets, next_edge.src);  
        int y = find(subsets, next_edge.dest);  
  
        if (x != y)  
        {  
            result[e++] = next_edge;  
            Union(subsets, x, y);  
        }  
    }  
    cout<<"Following are the edges in the constructed MST\n";  
    for (i = 0; i < e; ++i)  
        cout<<result[i].src<<" -- "<<result[i].dest<<" == "<<result[i].weight<<endl;  
    return;  
}  
```
### Mi rutina diaria:
	1. Levatarme
	2. Bañarme
	3. Vestire
	4. Desayunar
	5. Irme a la universidad
	6. Estudiar
	7. Almorzar
	8. Estudiar más
	9. Llegar a mi casa
	10. Dormir


