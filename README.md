# Проект: Введение в машинное обучение

<div class="Markdown base-markdown base-markdown_with-gallery markdown markdown_size_normal markdown_type_theory full-markdown"><h1>Рекомендация тарифов</h1><div class="paragraph">Поздравляем! Вы прошли курс в тренажёре. Самое время проверить знания и решить новую задачу машинного обучения. Выполнять работу вы будете самостоятельно.  </div><div class="paragraph">Когда закончите, отправьте работу на проверку ревьюеру: он пришлёт комментарии в течение суток. После этого нужно доработать проект и пройти повторную проверку. </div><div class="paragraph">Скорее всего, вы будете дорабатывать кейс по комментариям ещё несколько раз. Это нормально. </div><div class="paragraph">Проект завершён, когда ревьюер одобрит все доработки. </div><h1>Описание проекта</h1><div class="paragraph">Оператор мобильной связи «Мегалайн» выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра».</div><div class="paragraph">В вашем распоряжении данные о поведении клиентов, которые уже перешли на эти тарифы (из проекта курса «Статистический анализ данных»). Нужно построить модель для задачи классификации, которая выберет подходящий тариф. Предобработка данных не понадобится — вы её уже сделали.</div><div class="paragraph">Постройте модель с максимально большим значением <em>accuracy</em>. Чтобы сдать проект успешно, нужно довести долю правильных ответов по крайней мере до 0.75. Проверьте <em>accuracy</em> на тестовой выборке самостоятельно.</div><h3>Инструкция по выполнению проекта</h3><ol start="1"><li>Откройте файл с данными и изучите его. Путь к файлу: <code class="code-inline code-inline_theme_light">/datasets/users_behavior.csv</code>. </li><li>Разделите исходные данные на обучающую, валидационную и тестовую выборки.</li><li>Исследуйте качество разных моделей, меняя гиперпараметры. Кратко напишите выводы исследования.</li><li>Проверьте качество модели на тестовой выборке.</li><li>Дополнительное задание: проверьте модели на вменяемость. Ничего страшного, если не получится: эти данные сложнее тех, с которыми вы работали раньше. В следующем курсе подробнее об этом расскажем.</li></ol><h3>Описание данных</h3><div class="paragraph">Каждый объект в наборе данных — это информация о поведении одного пользователя за месяц. Известно:</div><ul><li><em>сalls</em> — количество звонков,</li><li><em>minutes</em> — суммарная длительность звонков в минутах,</li><li><em>messages</em> — количество sms-сообщений,</li><li><em>mb_used</em> — израсходованный интернет-трафик в Мб,</li><li><em>is_ultra</em> — каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0).</li></ul>
