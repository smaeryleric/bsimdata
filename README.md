#  Конфигурация баннера игры


---

## Параметры

### **Текстовые поля**
- **`Title_txt`**  
   Текст названия игры в стандартном баннере.

- **`Fullscreen_title_txt`**  
   Текст названия игры в полноэкранном баннере.

### **Изображения**
- **`Icon_img`**  
   Иконка игры в стандартном баннере.

- **`Fullscreen_icon_img`**  
   Иконка игры в полноэкранном баннере.

### **Интерактивные элементы**
- **`Link_image`**  
   Кнопка или изображение, которое перенаправляет пользователя на игру.

### **Объект баннера**
- **`Banner`**  
   Основной объект, содержащий все элементы баннера: текст, изображения и ссылки.

### **Ссылки для платформ**
- **`Android/Ios/Web_url`**  
   Прямая ссылка на JSON-файл с конфигурацией баннера. Этот файл содержит данные для конкретных платформ.

---

##  Использование
1.  Укажите значения для:
   - `Title_txt`
   - `Fullscreen_title_txt`
   - `Icon_img`
   - `Fullscreen_icon_img`

2. Задайте URL для `Link_image`, чтобы обеспечить переход к игре.

3. Убедитесь, что объект `Banner` включает все необходимые компоненты.

4. Добавьте ссылки на JSON-файлы для каждой платформы (`Android/Ios/Web_url`) для динамической загрузки данных.

---

## Пример структуры JSON

```json
{
  "Title_txt": "Название игры",
  "Fullscreen_title_txt": "Название игры (полноэкранный режим)",
  "Icon_img": "https://example.com/icon.png",
  "Fullscreen_icon_img": "https://example.com/fullscreen-icon.png",
  "Link_image": "https://example.com/game-link",
  "Banner": {
    "Title": "Название баннера",
    "Description": "Описание баннера"
  },
  "Android_url": "https://example.com/android-config.json",
  "Ios_url": "https://example.com/ios-config.json",
  "Web_url": "https://example.com/web-config.json"
}
