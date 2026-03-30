using UnityEngine;

public class Variaveis : MonoBehaviour
{
    int numero;
    float tempo;
    void Start()
    {
       
    }
    void Update()
    {
      tempo = tempo + Time.deltaTime;
      Debug.Log("Tempo: " + tempo);
    }
    

}
