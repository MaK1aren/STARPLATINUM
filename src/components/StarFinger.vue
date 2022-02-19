<template>

<button type="button" class="btn btn-primary">Проголосовать</button>
<button type="button" class="btn btn-secondary">Поддержка</button>
<button type="button" class="btn btn-success">Редактировать</button>
<button type="button" class="btn btn-danger">Зарегестрироваться</button>
<button type="button" class="btn btn-warning">Войти</button>
<button type="button" class="btn btn-info">Принять участие</button>
<button type="button" class="btn btn-light">Донат</button>
<button type="button" class="btn btn-dark" @click="$emit('increaseBy', 1)">Соревновая 11-ых классов</button>
<table class="table">
  <thead>
  <h1>Соревновая 9-ых классов (лидеры):</h1>
    <tr>
      <th scope="col">Место</th>
      <th scope="col">Имя</th>
      <th scope="col">Класс</th>
      <th scope="col">Предмет</th>
      <th scope="col">Баллы</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>Лёха</td>
      <td>9 А</td>
      <td>Русский</td>
      <td>100 (доп 12 баллов)</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Тарас</td>
      <td>9 Щ</td>
      <td>Русский</td>
      <td>100 (доп 8 баллов)</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td>Серёга</td>
      <td>9 У</td>
      <td> Русский</td>
      <td>100 (доп 2 балла)</td>
    </tr>
  </tbody>
</table>
</template>
<script>

</script>