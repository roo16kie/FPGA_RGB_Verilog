# FPGA_RGB_Verilog
Program 1.  使用兩顆 RGB LED 實作十字路口的紅綠燈。  
            綠燈時間15秒，LED 顯示秒數。 
            可用按鈕控制紅綠燈。 
            一個 RGB LED 綠燈或黃燈時，另一個一定是紅燈。 
            可調整綠燈秒數。
            
Program 2.  使用按鈕調整 RGB LED 的 RGB值。  
　　　　　　 botton 1 reset RGB 的 PWM 值。 
            botton 3, 4 分別為增加或減少 PWM 值。 
            switches 為 01 時，調整 R 的 PWM 值。 
            switches 為 10 時，調整 G 的 PWM 值。 
            switches 為 11 時，調整 B 的 PWM 值。 
            LED 會顯示 switches 對應的 RGB 的 PWM 值。 
            switches 為 00 時，按下 botton 2 顯示 RGB LED。
