<template>
  <div class="register">
    <b-row class="mt-5">
      <b-col md="8" offset-md="2">
        <b-card title="注册">
        <b-form>
          <b-form-group label="姓名">
            <b-form-input
              type="text"
              label="姓名"
              v-model="user.name"
              required
              placeholder="请输入姓名"
            ></b-form-input>
          </b-form-group>
          <b-form-group label="手机号">
            <b-form-input
              type="text"
              v-model="user.mobile"
              required
              placeholder="请输入手机号"
            ></b-form-input>
          </b-form-group>
          <b-form-group  label="密码">
            <b-form-input
              type="password"
              label="密码"
              v-model="user.password"
              required
              placeholder="请输入密码"
            ></b-form-input>
          </b-form-group>
          <b-form-group>
              <b-button variant="outline-primary" block>注册</b-button>
          </b-form-group>
        </b-form>
        </b-card>
      </b-col>
    </b-row>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        user: {
          name: '',
          mobile: '',
          password: '',
        },
      }
    },
  }
</script>

