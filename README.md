using UnityEngine;

public class Variaveis : MonoBehaviour
{
    int vidaPlayer = 10 ;
    int atackEnemy = 5 ;
    float jumpForce = 5.5f ;
    bool mortePlayer = false;
    string nomePlayer = "Julia";
    void Start()
    {
         
    }

    void Update()
    {
        print(vidaPlayer);
    }
}
