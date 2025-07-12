# unity_journey

## serialize variable 

```C#
public class mover : MonoBehaviour
{
    float xValue = 0.0f;
    [SerializeField] float yValue = 0.1f;
    float zValue = 0.0f;
}
```

<img width="1920" height="1031" alt="image" src="https://github.com/user-attachments/assets/2b07ef99-dcc9-4d68-9774-fbeba2ee91f5" />

## Exercice 

Make al the three variables serialized and accessable from the instrector 

```C#
public class mover : MonoBehaviour
{
    [SerializeField] float xValue = 0.0f;
    [SerializeField] float yValue = 0.1f;
    [SerializeField] float zValue = 0.0f;
}
```
