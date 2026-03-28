using UnityEngine;

public class Variaveis : MonoBehaviour
{
    int numero1, numero2, resultadoSub ;
    int vidaPlayer = 100, ataqueInimigo = 10, vidaAtual = 40, ataqueRecebido;

    void Start()
    {
       int ataqueRecebido = vida(vidaPlayer, ataqueInimigo, vidaAtual);
       Debug.Log("O ataque recebido é: " + ataqueRecebido + " golpes");
    }
    void Update()
    {
        
    }
    
    int vida(int vidaPlayer, int ataqueInimigo, int vidaAtual)
    {
       ataqueRecebido = (vidaPlayer - vidaAtual)/ataqueInimigo;
         return ataqueRecebido;
    }
}
