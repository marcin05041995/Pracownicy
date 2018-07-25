<template>
<div class="AddWorker">
  <div style=clear:both;></div>
  <h1>{{Message}}</h1>
    <button class="btn btn-primary">Dodaj pracownika</button>
    <button class="btn btn-success">Edytuj</button>
    <button class="btn btn-info">Szczegóły</button>
    <button class="btn btn-danger">Usuń</button>

      <form>
        <div class="well">
            <h4>Dane pracownika</h4>
            <div class="form-group">
                <label>Imie</label>
                <input type="text" class="form-control"  placeholder="Podaj imie" >
            </div>
            <div class="form-group">
                <label>Nazwisko</label>
                <input type="text" class="form-control"  placeholder="Podaj nazwisko" >
            </div>
            <div class="form-group">
                <label>Data urodzenia</label>
                <input type="text" class="form-control"  placeholder="Podaj date" >
            </div>
            <div class="form-group">
                <label>Numer telefonu</label>
                <input type="text" class="form-control"  placeholder="Podaj numer" >
            </div>

        </div>
    </form>
</div>


</template>

<script>
export default{
  name: 'AddWorker',
  data(){
    return{
      Message: 'Wybierz akcję której chcesz dokonać.'
    }
  }
}
</script>
<style>
.btn{
  width:150px;
  margin-top:10px;
}
.well{
  margin-top:10px;
}
  .form-group{
    width:25%;
    margin-left:auto;
    margin-right:auto;
  }
</style>
