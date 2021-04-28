<template>
  <form class="add-form">
    <div class="form-control">
      <label>Task</label>
      <input type="text" placeholder="Add Task" />
    </div>
    <div class="form-control">
      <label>Day & Time</label>
      <input type="text" name="day" placeholder="Add Day & Time" />
    </div>
    <div class="form-control form-control-check">
      <label>Set Reminder</label>
      <input type="checkbox" name="reminder" />
    </div>
    <input type="submit" value="Save Task" class="btn btn-block" />
  </form>
</template>

<script>
export default {
  name: "AddTask",
};
</script>

<style scoped>
.add-form {
  margin-bottom: 40px;
}
.form-control {
  margin: 20px 0;
}

.form-control label {
  display: block;
}
.form-control input {
  width: 100%;
  height: 40px;
  margin: 05px;
  padding: 3px 7px;
  font-size: 17px;
}

.form-control-check {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.form-control-check label {
  flex: 1;
}
.form-control-check input {
  flex: 2;
  height: 20px;
}
</style>
