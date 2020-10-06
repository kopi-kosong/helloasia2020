<template>
  <div>
    <div class="uk-section uk-section-primary">
      <div class="uk-container uk-text-center">
      <img src="../public/b1.png" alt="hello" width="500" height="600">
           
        <h1 class="uk-margin-large-top">Video IT Help Desk Demo</h1>
        <p class="uk-text-lead">This demo showcases a simulation of a virtual IT Help Desk center where remote staffs queue up to talk to available IT specialists.</p>
      </div>
    </div>
    <div class="uk-section uk-section-default">
      <div class="container">
        <div class="route-home uk-flex-center" uk-grid>
           
          <div>
  
            <router-link to="/agent" class="uk-button uk-button-primary uk-button-large"><i uk-icon="icon: cog" style="color:#000000; padding-left: 0px;padding-right: 10px;"></i>  Join as IT Support Engineer</router-link>
          </div>

          <div>
        
            <router-link to="/caller" class="uk-button uk-button-primary uk-button-large"><i uk-icon="icon: users" style="color:#000000;  padding-left: 0px;padding-right: 10px;"></i>   Join as Staff</router-link>
              
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
