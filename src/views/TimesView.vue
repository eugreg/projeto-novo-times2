<template>
  <div class="container">
    <div class="title">
      <h2>Gerenciamento De Time</h2>
    </div>
    <div class="form-input">
      <input type="text" />
      <button>salvar</button>
    </div>
    <div class="list-times">
      <table>
        <thead>
          <tr>
            <th>ID</th>
            <th>Nome</th>
            <th>Açoes</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>1</td>
            <td>Time 1</td>
            <td>??</td>
          </tr>
          <tr>
            <td>2</td>
            <td>Time 2</td>
            <td>????</td>
          </tr>
          <tr>
            <td>3</td>
            <td>Time 3</td>
            <td>???</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<style>
.list-times {
  display: flex;
  justify-content: center;
}
table {
  width: 50%;
  margin: 0 auto;
  border-collapse: collapse;
  border-radius: 10px;
}
table tr td {
  border: 1px solid #ccc;
  padding: 10px;
}
table tr th {
  border: 1px solid #ccc;
  padding: 10px;
  font-weight: bold;
}
.title {
  margin-top: 2rem auto;
  display: flex;
  justify-content: center;
}
.form-input {
  margin-top: 10px;
  display: flex;
  justify-content: center;
}
.form-input input {
  width: 60%;
  height: 40px;
  border: 1px solid #ccc;
  border-radius: 10px;
  padding: 0 10px;
}
.form-input button {
  width: 30%;
  height: 40px;
  border: 1px solid #blue;
  border-radius: 10px;
  background-color: #green;
  color: black;
  font-weight: bold;
  cursor: pointer;
}
</style>
