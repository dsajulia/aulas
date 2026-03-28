using UnityEngine;

public class Variaveis : MonoBehaviour
{
    int numero1 ;
        int numero2 ;

    void Start()
    {
       numero1 = 10;
       numero2 = 20;
       Soma();
       Multiplicacao(5, 10);   
    }
    void Update()
    {
        
    }
    void Soma()
    {
        int resultado;
        resultado = numero1 + numero2;
        Debug.Log(resultado);
    }
    void Multiplicacao(int numA, int numB)
    {
        int resultado;
        resultado = numA * numB;
        Debug.Log(resultado);
    }
}
