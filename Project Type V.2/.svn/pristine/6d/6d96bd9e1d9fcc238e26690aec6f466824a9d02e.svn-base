using UnityEngine;
using UnityEngine.UI;
using System.Collections;

public class BackgroudScrolling : MonoBehaviour {

    [Range(-4,4)]
    public float _speed = 1;
	
	// Update is called once per frame
	void Update () {

        GetComponent<RawImage>().uvRect = new Rect(new Vector2(Time.time * _speed, 0.0f), Vector2.one);
	}
}
