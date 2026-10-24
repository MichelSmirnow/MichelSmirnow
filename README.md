<div align="center">

  <!-- ================================
       КВАДРАТНЫЙ КОНТЕЙНЕР ПРОФИЛЯ
       ================================ -->
  <div style="
    width: 600px;
    height: 600px;
    border: 1px solid #e1e4e8;
    border-radius: 12px;
    overflow: hidden;
    margin: 30px auto;
    box-shadow: 0 4px 14px rgba(0, 0, 0, 0.08);
    display: flex;
  ">

    <!-- Левая часть: вертикальное изображение -->
    <div style="
      width: 240px;
      height: 100%;
      background: #fafbfc;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 16px;
      box-sizing: border-box;
    ">
      <img
        src="kurisu.png"
        alt="Аватар профиля"
        style="
          max-width: 100%;
          max-height: 100%;
          width: auto;
          height: auto;
          object-fit: contain;
          border-radius: 6px;
        "
      />
    </div>

    <!-- Правая часть: текст, прижатый к изображению -->
    <div style="
      flex: 1;
      height: 100%;
      padding: 24px 6px 24px 12px;
      box-sizing: border-box;
      display: flex;
      align-items: center;
      text-align: left;
    ">
      <p style="
        margin: 0;
        font-size: 15px;
        line-height: 1.7;
        color: #24292e;
        word-wrap: break-word;
      ">
        Михаил Смирнов, я студент IT направления. В моей жизни было много нереализованных проектов, и сейчас я наконец-то за них взялся, и с использованием агента собираюсь их все довести до конца. Моя тактика - создать проект вручную, добавить весь функционал с помощью агента и затем вручную дошлифовать, изменить, переправить - привести проект к готовому виду. Фанат Врат Штейна
      </p>
    </div>

  </div>

</div>

---

### Как использовать

1. Загрузите `kurisu.png` в корень своего репозитория (или в папку, например `assets/`).
2. Обновите `src="kurisu.png"` в шаблоне выше на актуальный путь к картинке.
3. Измените `width` / `height` контейнера (сейчас `600px × 600px`) и ширину картинки (`240px`), если нужно подогнать размер под себя.
4. Допишите остальной текст и разделы (навыки, проекты, контакты) ниже или справа, по своему вкусу.
