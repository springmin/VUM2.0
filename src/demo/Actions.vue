<template>
  <div class="page">
    <simple-header title="Actions" :back-link="true"></simple-header>
    <Content>
      <div class='demos-content-padded'>
        <p><m-button @click.native="showActions()">Show Actions</m-button></p>
      </div>
    </Content>
    <actions :show="show">
      <action-group>
        <action-button @click="publish()">Publish</action-button>
        <action-button @click="save()">Save</action-button>
        <action-button class="color-danger" @click="save()">Delete</action-button>
      </action-group>
    </actions>
  </div>
</template>

<script>
import Content from '../components/content'
import { SimpleHeader } from '../components/header'
import { Button } from '../components/buttons'
import { Actions, ActionButton, ActionGroup } from '../components/actions'

export default {
  components: {
    Content,
    SimpleHeader,
    'm-button': Button,
    'actions': Actions,
    'action-button': ActionButton,
    'action-group': ActionGroup
  },
  data () {
    return {
      show: false
    }
  },
  methods: {
    showActions () {
      this.show = true
    },
    publish () {
      this.show = false
    },
    save () {
      this.show = false
    },
    delete () {
      this.show = false
    }
  }
}
</script>
