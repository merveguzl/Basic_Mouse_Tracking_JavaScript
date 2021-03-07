## Mouse Tracking
Mouse hareketlerinin izlenmesi için showCoords fonksiyonu kullanılmakta. Aynı fonksiyonu bir html taginin onclick fonksiyonuna verdiğinizde mouse'ın tıkladığı noktanın koordinatlarına sahip olursunuz.

    function showCoords(event) {
              var x = event.clientX;
              var y = event.clientY;
              var coor = "X coords: " + x + ", Y coords: " + y;
              document.getElementById("demo").innerHTML = coor;
            }

Mouse'ın her hareketinde p taginin içerisini boşaltmak için clearCoor fonksiyonu kullanılmakta.

     function clearCoor() {
                  document.getElementById("demo").innerHTML = "";
                }

