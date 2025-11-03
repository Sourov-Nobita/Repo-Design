
<p align="center">
  <svg width="200" height="200" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <radialGradient id="grad">
        <stop offset="0%" stop-color="#00FFFF">
          <animate attributeName="stop-color" values="#00FFFF;#8A2BE2;#00FFFF" dur="4s" repeatCount="indefinite"/>
        </stop>
        <stop offset="100%" stop-color="#000000" />
      </radialGradient>
    </defs>
    <circle cx="100" cy="100" r="80" fill="url(#grad)">
      <animate attributeName="r" values="70;90;70" dur="3s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="rotate" from="0 100 100" to="360 100 100" dur="6s" repeatCount="indefinite"/>
    </circle>
  </svg>
</p>




<p align="center">
  <svg viewBox="0 0 1200 120" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="wave" gradientTransform="rotate(90)">
        <stop offset="0%" stop-color="#00FFFF">
          <animate attributeName="stop-color" values="#00FFFF;#8A2BE2;#00FFFF" dur="3s" repeatCount="indefinite"/>
        </stop>
        <stop offset="100%" stop-color="#8A2BE2">
          <animate attributeName="stop-color" values="#8A2BE2;#00FFFF;#8A2BE2" dur="3s" repeatCount="indefinite"/>
        </stop>
      </linearGradient>
    </defs>
    <path fill="none" stroke="url(#wave)" stroke-width="4">
      <animate attributeName="d" dur="6s" repeatCount="indefinite"
        values="M0,60 Q300,100 600,60 T1200,60;
                M0,50 Q300,10 600,50 T1200,50;
                M0,60 Q300,100 600,60 T1200,60"/>
    </path>
  </svg>
</p>





<p align="center">
  <svg width="200" height="200" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
    <circle cx="100" cy="100" r="40" stroke="#00FFFF" stroke-width="3" fill="none">
      <animate attributeName="r" values="40;70;40" dur="2.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="1;0;1" dur="2.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="100" cy="100" r="60" stroke="#8A2BE2" stroke-width="2" fill="none">
      <animate attributeName="r" values="60;90;60" dur="3s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="1;0;1" dur="3s" repeatCount="indefinite"/>
    </circle>
  </svg>
</p>
