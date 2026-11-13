
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#f7f7fb">
<title>Taskly — твой день под контролем</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700;800&family=Manrope:wght@400;500;600;700;800&display=swap');

:root {
  --ink: #202238;
  --muted: #8b8fa5;
  --line: #ececf3;
  --purple: #6c5ce7;
  --purple2: #8b7cf6;
  --lav: #f0edff;
  --bg: #f7f7fb;
  --white: #fff;
  --green: #24a879;
  --red: #e56b78;
  --shadow: 0 24px 70px rgba(42,39,89,.09);
}

* { box-sizing: border-box; }

body {
  margin: 0;
  background: var(--bg);
  color: var(--ink);
  font-family: 'DM Sans', sans-serif;
  min-height: 100vh;
}

button, input { font: inherit; }
button { cursor: pointer; }

.shell {
  max-width: 1180px;
  margin: auto;
  padding: 34px 30px 50px;
}

.topbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 36px;
}

.brand {
  display: flex;
  align-items: center;
  gap: 11px;
  font: 800 22px Manrope, sans-serif;
  letter-spacing: -.8px;
}

.brand-mark {
  width: 39px;
  height: 39px;
  border-radius: 13px;
  background: linear-gradient(135deg,var(--purple),#9b8cff);
  display: grid;
  place-items: center;
  color: #fff;
  box-shadow: 0 8px 18px #7568e64d;
}

.brand-mark svg { width: 21px; }

.date-pill {
  padding: 10px 15px;
  background: #fff;
  border: 1px solid var(--line);
  border-radius: 30px;
  color: var(--muted);
  font-size: 13px;
}

.hero {
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
  gap: 24px;
  margin-bottom: 28px;
}

.kicker {
  font-size: 11px;
  font-weight: 800;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: var(--purple);
  margin-bottom: 10px;
}

h1 {
  font: 800 clamp(32px,5vw,46px)/1.12 Manrope,sans-serif;
  letter-spacing: -2px;
  margin: 0 0 9px;
}

.sub { color: var(--muted); font-size: 15px; margin: 0; }

.hero-note {
  color: #777b91;
  font-size: 13px;
  text-align: right;
  line-height: 1.6;
}

.layout {
  display: grid;
  grid-template-columns: minmax(0,1fr) 290px;
  gap: 22px;
  align-items: start;
}

.main-card, .side-card {
  background: var(--white);
  border: 1px solid #efeff5;
  border-radius: 22px;
  box-shadow: var(--shadow);
}

.main-card { padding: 25px; }

.add-label {
  font-size: 13px;
  font-weight: 700;
  margin: 0 0 12px;
}

.add-row { display: flex; gap: 10px; }

.task-input {
  flex: 1;
  min-width: 0;
  border: 1px solid var(--line);
  background: #fafaff;
  border-radius: 13px;
  padding: 15px 16px;
  outline: none;
  color: var(--ink);
  transition: .2s;
}

.task-input:focus {
  border-color: #a69cf5;
  box-shadow: 0 0 0 4px #6c5ce714;
  background: #fff;
}

.task-input::placeholder { color: #a6a8b8; }

.add-btn {
  border: 0;
  border-radius: 13px;
  padding: 0 20px;
  color: #fff;
  font-weight: 700;
  background: linear-gradient(135deg,var(--purple),var(--purple2));
  box-shadow: 0 8px 17px #7669e638;
  transition: .2s;
}

.add-btn:hover {
  transform: translateY(-2px);
  box-shadow: 0 11px 22px #7669e64a;
}

.toolbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 12px;
  margin: 27px 0 14px;
}

.section-title { font: 800 16px Manrope,sans-serif; }

.filters {
  display: flex;
  gap: 5px;
  background: #f6f6fa;
  padding: 4px;
  border-radius: 11px;
}

.filter {
  border: 0;
  background: transparent;
  color: var(--muted);
  padding: 8px 12px;
  border-radius: 8px;
  font-size: 12px;
  font-weight: 700;
}

.filter.active {
  background: #fff;
  color: var(--purple);
  box-shadow: 0 2px 8px #25234b0d;
}

.task-list { list-style: none; padding: 0; margin: 0; }

.task {
  display: flex;
  align-items: center;
  gap: 13px;
  padding: 15px 5px;
  border-top: 1px solid #f1f1f6;
  animation: rise .2s ease;
}

@keyframes rise {
  from { opacity: 0; transform: translateY(5px); }
  to { opacity: 1; transform: none; }
}

.check {
  width: 22px;
  height: 22px;
  flex: 0 0 22px;
  border: 1.7px solid #d4d5e1;
  border-radius: 7px;
  background: #fff;
  display: grid;
  place-items: center;
  color: #fff;
  transition: .18s;
}

.check:hover { border-color: var(--purple); }

.task.done .check {
  background: var(--green);
  border-color: var(--green);
}

.check svg { width: 14px; height: 14px; }

.task-copy { flex: 1; min-width: 0; }

.task-name {
  font-size: 14px;
  line-height: 1.45;
  overflow-wrap: anywhere;
}

.task.done .task-name {
  color: #a5a7b5;
  text-decoration: line-through;
}

.task-meta {
  font-size: 11px;
  color: #a4a6b5;
  margin-top: 4px;
}

.delete {
  border: 0;
  background: transparent;
  color: #b5b7c4;
  width: 34px;
  height: 34px;
  border-radius: 9px;
  font-size: 20px;
  opacity: .7;
}

.delete:hover {
  background: #fff0f1;
  color: var(--red);
  opacity: 1;
}

.empty {
  text-align: center;
  padding: 45px 12px 35px;
  color: var(--muted);
}

.empty-emoji {
  width: 54px;
  height: 54px;
  border-radius: 18px;
  background: var(--lav);
  color: var(--purple);
  display: grid;
  place-items: center;
  font-size: 25px;
  margin: 0 auto 13px;
}

.empty strong {
  display: block;
  color: var(--ink);
  font: 700 15px Manrope;
  margin-bottom: 5px;
}

.empty span { font-size: 13px; }

.side { display: grid; gap: 17px; }
.side-card { padding: 21px; }

.side-heading {
  font: 800 14px Manrope;
  margin: 0 0 17px;
}

.progress-top {
  display: flex;
  align-items: baseline;
  justify-content: space-between;
  margin-bottom: 12px;
}

.progress-number {
  font: 800 30px Manrope;
  letter-spacing: -1.5px;
}

.progress-caption { font-size: 11px; color: var(--muted); }

.progress-track {
  height: 9px;
  background: #f0eff7;
  border-radius: 20px;
  overflow: hidden;
}

.progress-fill {
  height: 100%;
  width: 0;
  background: linear-gradient(90deg,var(--purple),#a394ff);
  border-radius: 20px;
  transition: width .3s;
}

.progress-foot {
  display: flex;
  justify-content: space-between;
  margin-top: 12px;
  font-size: 11px;
  color: var(--muted);
}

.stat-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 10px;
}

.stat { padding: 14px; border-radius: 14px; background: #fafaff; }

.stat-icon {
  width: 29px;
  height: 29px;
  border-radius: 9px;
  display: grid;
  place-items: center;
  margin-bottom: 10px;
  font-size: 14px;
}

.stat:nth-child(1) .stat-icon {
  background: #efedff;
  color: var(--purple);
}

.stat:nth-child(2) .stat-icon {
  background: #e8f8f1;
  color: var(--green);
}

.stat-num { font: 800 22px Manrope; }
.stat-label { font-size: 11px; color: var(--muted); margin-top: 2px; }

.tip {
  background: linear-gradient(135deg,#29264c,#51468f);
  color: #fff;
  border: 0;
  overflow: hidden;
  position: relative;
}

.tip:after {
  content: "✦";
  position: absolute;
  right: 15px;
  top: 9px;
  font-size: 57px;
  color: #ffffff16;
}

.tip .side-heading { color: #fff; }

.tip p {
  font-size: 12px;
  line-height: 1.65;
  color: #d5d1f3;
  margin: 0;
  max-width: 210px;
}

.footer {
  text-align: center;
  color: #b0b2bf;
  font-size: 11px;
  margin-top: 24px;
}

@media(max-width:820px) {
  .layout { grid-template-columns: 1fr; }
  .side { grid-template-columns: 1fr 1fr; }
  .tip { grid-column: 1/-1; }
}

@media(max-width:560px) {
  .shell { padding: 22px 14px 35px; }
  .topbar { margin-bottom: 27px; }
  .hero { display: block; }
  .hero-note { display: none; }
  .main-card { padding: 18px 15px; }
  .add-row { flex-direction: column; }
  .add-btn { padding: 14px; }
  .toolbar { align-items: flex-start; flex-direction: column; }
  .filters { width: 100%; }
  .filter { flex: 1; }
  .side { grid-template-columns: 1fr 1fr; }
  .side-card { padding: 17px; }
  .tip { grid-column: 1/-1; }
  .date-pill { font-size: 11px; padding: 8px 11px; }
}
</style>
</head>

<body>
<div class="shell">
  <header class="topbar">
    <div class="brand">
      <div class="brand-mark">
        <svg viewBox="0 0 24 24" fill="none">
          <path d="m5 12 4.2 4.2L19 6.8"
            stroke="currentColor" stroke-width="2.8"
            stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
      </div>
      taskly
    </div>
    <div class="date-pill" id="today">Твой план на сегодня</div>
  </header>

  <section class="hero">
    <div>
      <div class="kicker">Твой личный планировщик</div>
      <h1>День под контролем<span style="color:var(--purple)">.</span></h1>
      <p class="sub">Записывай важное. Отмечай сделанное. Двигайся вперёд.</p>
    </div>
    <div class="hero-note">
      Маленький шаг сегодня<br>
      это большой результат завтра ✨
    </div>
  </section>

  <div class="layout">
    <main class="main-card">
      <form id="task-form">
        <p class="add-label">Что нужно сделать?</p>
        <div class="add-row">
          <input class="task-input" id="task-input"
            type="text" maxlength="180"
            placeholder="Например, подготовить презентацию..."
            autocomplete="off" aria-label="Новая задача">
          <button class="add-btn" type="submit">＋ Добавить задачу</button>
        </div>
      </form>

      <div class="toolbar">
        <div class="section-title">Мои задачи</div>
        <nav class="filters" aria-label="Фильтры">
          <button class="filter active" data-filter="all" type="button">Все</button>
          <button class="filter" data-filter="active" type="button">В процессе</button>
          <button class="filter" data-filter="done" type="button">Готово</button>
        </nav>
      </div>

      <ul class="task-list" id="task-list"></ul>

      <div class="empty" id="empty">
        <div class="empty-emoji">✦</div>
        <strong>Пока никаких задач</strong>
        <span>Добавь первую задачу и начни свой день!</span>
      </div>
    </main>

    <aside class="side">
      <section class="side-card">
        <h2 class="side-heading">Твой прогресс</h2>
        <div class="progress-top">
          <div class="progress-number" id="percent">0%</div>
          <div class="progress-caption">выполнено</div>
        </div>
        <div class="progress-track">
          <div class="progress-fill" id="progress-fill"></div>
        </div>
        <div class="progress-foot">
          <span id="progress-done">0 готово</span>
          <span id="progress-total">из 0 задач</span>
        </div>
      </section>

      <section class="side-card">
        <h2 class="side-heading">Короткая сводка</h2>
        <div class="stat-grid">
          <div class="stat">
            <div class="stat-icon">☰</div>
            <div class="stat-num" id="total">0</div>
            <div class="stat-label">Всего задач</div>
          </div>
          <div class="stat">
            <div class="stat-icon">✓</div>
            <div class="stat-num" id="completed">0</div>
            <div class="stat-label">Выполнено</div>
          </div>
        </div>
      </section>

      <section class="side-card tip">
        <h2 class="side-heading">Маленький совет</h2>
        <p>Начни с самой простой задачи. Первый выполненный пункт задаёт хороший темп всему дню.</p>
      </section>
    </aside>
  </div>

  <div class="footer">
    TASKLY · ТВОИ ЗАДАЧИ СОХРАНЯЮТСЯ АВТОМАТИЧЕСКИ В ЭТОМ БРАУЗЕРЕ
  </div>
</div>

<script>
const KEY = 'taskly-tasks-v2';

const form = document.getElementById('task-form');
const input = document.getElementById('task-input');
const list = document.getElementById('task-list');
const empty = document.getElementById('empty');

let tasks = readTasks();
let filter = 'all';

// Загружаем задачи из localStorage
function readTasks() {
  try {
    const x = JSON.parse(localStorage.getItem(KEY) || '[]');
    return Array.isArray(x)
      ? x.filter(t =>
          t &&
          typeof t.id === 'string' &&
          typeof t.text === 'string' &&
          typeof t.done === 'boolean'
        )
      : [];
  } catch {
    return [];
  }
}

// Сохраняем задачи
function save() {
  localStorage.setItem(KEY, JSON.stringify(tasks));
}

// Отображаем список задач
function render() {
  list.replaceChildren();

  const shown = tasks.filter(t =>
    filter === 'all' ||
    (filter === 'active' && !t.done) ||
    (filter === 'done' && t.done)
  );

  empty.hidden = shown.length > 0;

  empty.querySelector('strong').textContent =
    tasks.length === 0
      ? 'Пока никаких задач'
      : 'Здесь пока пусто';

  empty.querySelector('span').textContent =
    tasks.length === 0
      ? 'Добавь первую задачу и начни свой день!'
      : 'Попробуй выбрать другой фильтр.';

  shown.forEach(t => {
    const li = document.createElement('li');
    li.className = 'task' + (t.done ? ' done' : '');

    // Кнопка выполнения
    const check = document.createElement('button');
    check.className = 'check';
    check.type = 'button';

    check.setAttribute(
      'aria-label',
      t.done ? 'Отметить как активную' : 'Отметить как выполненную'
    );

    if (t.done) {
      check.innerHTML = `
        <svg viewBox="0 0 20 20" fill="none">
          <path d="m4 10 4 4 8-8"
            stroke="currentColor"
            stroke-width="2.2"
            stroke-linecap="round"
            stroke-linejoin="round"/>
        </svg>`;
    }

    check.onclick = () => {
      t.done = !t.done;
      save();
      render();
    };

    // Текст задачи
    const copy = document.createElement('div');
    copy.className = 'task-copy';

    const name = document.createElement('div');
    name.className = 'task-name';
    name.textContent = t.text;

    const meta = document.createElement('div');
    meta.className = 'task-meta';
    meta.textContent = t.done ? 'Выполнено' : 'В списке задач';

    copy.append(name, meta);

    // Кнопка удаления
    const del = document.createElement('button');
    del.className = 'delete';
    del.type = 'button';
    del.textContent = '×';
    del.setAttribute('aria-label', 'Удалить задачу');

    del.onclick = () => {
      tasks = tasks.filter(x => x.id !== t.id);
      save();
      render();
    };

    li.append(check, copy, del);
    list.append(li);
  });

  // Обновляем статистику
  const done = tasks.filter(t => t.done).length;
  const total = tasks.length;
  const pct = total ? Math.round(done / total * 100) : 0;

  document.getElementById('total').textContent = total;
  document.getElementById('completed').textContent = done;

  document.getElementById('percent').textContent = pct + '%';
  document.getElementById('progress-fill').style.width = pct + '%';

  document.getElementById('progress-done').textContent = done + ' готово';
  document.getElementById('progress-total').textContent = 'из ' + total + ' задач';

  // Подсветка выбранного фильтра
  document.querySelectorAll('.filter').forEach(b => {
    const on = b.dataset.filter === filter;
    b.classList.toggle('active', on);
    b.setAttribute('aria-pressed', String(on));
  });
}

// Добавление новой задачи
form.addEventListener('submit', e => {
  e.preventDefault();

  const text = input.value.trim();

  if (!text) {
    input.focus();
    return;
  }

  tasks.unshift({
    id: Date.now().toString(36) + Math.random().toString(36).slice(2),
    text,
    done: false
  });

  save();
  input.value = '';
  filter = 'all';
  render();
  input.focus();
});

// Переключение фильтров
document.querySelectorAll('.filter').forEach(b => {
  b.addEventListener('click', () => {
    filter = b.dataset.filter;
    render();
  });
});

// Текущая дата
const now = new Date();

document.getElementById('today').textContent =
  new Intl.DateTimeFormat('ru-RU', {
    weekday: 'long',
    day: 'numeric',
    month: 'long'
  }).format(now);

// Первый запуск
render();
</script>
</body>
</html>
