#  Конфигурация баннера игры


---

## Параметры Banner.cs

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
   "show": true,
   "imgurl":"https://raw.githubusercontent.com/smaeryleric/bsimdata/main/dopa.png",
   "url":"https://play.google.com/store/apps/details?id=com.mobicone.a4erase",
   "title":"",
   "linkimg":"https://raw.githubusercontent.com/smaeryleric/bsimdata/main/en_badge_web_generic.png" 
}
