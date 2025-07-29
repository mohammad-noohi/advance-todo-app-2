```html
<div class="todo todo--active">
  <div class="todo__header">
    <div class="todo__header-left">
      <p class="todo__title">todo title</p>
      <span class="todo__cat"># category</span>
    </div>

    <div class="todo__header-right">
      <span class="todo__timer-indicator">2025/03/12</span>
      <div class="todo__stars"> ⭐⭐⭐⭐⭐ </div>
    </div>
  </div>
  <div class="todo__body">
    <p class="todo__desc">
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Maiores, ratione corrupti. Autem, eius. Optio obcaecati dicta nesciunt quae sed est maxime totam sit! Velit illo reprehenderit provident
      assumenda recusandae quaerat. Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptates maiores, nisi at ullam, tempora tenetur architecto sapiente magni repellat quia cumque
      perspiciatis! Possimus tempore minus consequuntur eum sit, fugit illo?
    </p>
  </div>
  <div class="todo__footer">
    <div class="todo__actions">
      <button class="todo__action-btn">
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-trash2 icon" viewBox="0 0 16 16">
          <path
            d="M14 3a.7.7 0 0 1-.037.225l-1.684 10.104A2 2 0 0 1 10.305 15H5.694a2 2 0 0 1-1.973-1.671L2.037 3.225A.7.7 0 0 1 2 3c0-1.105 2.686-2 6-2s6 .895 6 2M3.215 4.207l1.493 8.957a1 1 0 0 0 .986.836h4.612a1 1 0 0 0 .986-.836l1.493-8.957C11.69 4.689 9.954 5 8 5s-3.69-.311-4.785-.793" />
        </svg>
      </button>
      <button class="todo__action-btn">
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-pen icon" viewBox="0 0 16 16">
          <path
            d="m13.498.795.149-.149a1.207 1.207 0 1 1 1.707 1.708l-.149.148a1.5 1.5 0 0 1-.059 2.059L4.854 14.854a.5.5 0 0 1-.233.131l-4 1a.5.5 0 0 1-.606-.606l1-4a.5.5 0 0 1 .131-.232l9.642-9.642a.5.5 0 0 0-.642.056L6.854 4.854a.5.5 0 1 1-.708-.708L9.44.854A1.5 1.5 0 0 1 11.5.796a1.5 1.5 0 0 1 1.998-.001m-.644.766a.5.5 0 0 0-.707 0L1.95 11.756l-.764 3.057 3.057-.764L14.44 3.854a.5.5 0 0 0 0-.708z" />
        </svg>
      </button>
      <button class="todo__action-btn">
        <!-- uncomplete -->
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-check2 icon" viewBox="0 0 16 16">
          <path d="M13.854 3.646a.5.5 0 0 1 0 .708l-7 7a.5.5 0 0 1-.708 0l-3.5-3.5a.5.5 0 1 1 .708-.708L6.5 10.293l6.646-6.647a.5.5 0 0 1 .708 0" />
        </svg>
        <!-- completeted -->
        <!-- <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-check2-all icon" viewBox="0 0 16 16">
                      <path
                        d="M12.354 4.354a.5.5 0 0 0-.708-.708L5 10.293 1.854 7.146a.5.5 0 1 0-.708.708l3.5 3.5a.5.5 0 0 0 .708 0zm-4.208 7-.896-.897.707-.707.543.543 6.646-6.647a.5.5 0 0 1 .708.708l-7 7a.5.5 0 0 1-.708 0" />
                      <path d="m5.354 7.146.896.897-.707.707-.897-.896a.5.5 0 1 1 .708-.708" />
                    </svg> -->
      </button>
      <button class="todo__action-btn">
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-stopwatch icon" viewBox="0 0 16 16">
          <path d="M8.5 5.6a.5.5 0 1 0-1 0v2.9h-3a.5.5 0 0 0 0 1H8a.5.5 0 0 0 .5-.5z" />
          <path
            d="M6.5 1A.5.5 0 0 1 7 .5h2a.5.5 0 0 1 0 1v.57c1.36.196 2.594.78 3.584 1.64l.012-.013.354-.354-.354-.353a.5.5 0 0 1 .707-.708l1.414 1.415a.5.5 0 1 1-.707.707l-.353-.354-.354.354-.013.012A7 7 0 1 1 7 2.071V1.5a.5.5 0 0 1-.5-.5M8 3a6 6 0 1 0 .001 12A6 6 0 0 0 8 3" />
        </svg>
      </button>
    </div>
    <span class="todo__time">12:30:21</span>
  </div>
</div>
```
