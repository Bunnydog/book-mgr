<template>
  <div class="auth">
    <div class="bg-img"></div>
    <div class="title">
      <img src="../../assets/img/title-logo.png" alt="" />
      <h2>图书管理系统</h2>
    </div>

    <div class="form">
      <a-tabs default-active-key="1">
        <a-tab-pane key="1" tab="登录">
          <div class="item">
            <a-input size="large" placeholder="账号">
              <template #prefix>
                <UserOutlined />
              </template>
            </a-input>
          </div>
          <div class="item">
            <a-input size="large" type="password" placeholder="密码">
              <template #prefix>
                <LockOutlined />
              </template>
            </a-input>
          </div>
          <div class="item">
            <a href="javascript:;">忘记密码</a>
          </div>

          <div class="item">
            <a-button size="large" type="primary"> 登入 </a-button>
          </div>
        </a-tab-pane>

        <a-tab-pane key="2" tab="注册">
          <div class="item">
            <a-input size="large" placeholder="账号">
              <template #prefix>
                <UserOutlined />
              </template>
            </a-input>
          </div>
          <div class="item">
            <a-input size="large" type="password" placeholder="密码">
              <template #prefix>
                <LockOutlined />
              </template>
            </a-input>
          </div>
          <div class="item">
            <a-input size="large" placeholder="邀请码" >
             
              <template #prefix>
                 <MailOutlined />
              </template>
            </a-input>
          </div>
          <div class="item">
            <a-button size="large" type="primary"> 注册 </a-button>
          </div>
        </a-tab-pane>
      </a-tabs>
    </div>
  </div>
</template>

<script src = './index.js'>
</script>


<style lang="scss" scoped>
@import "./index.scss";
</style>