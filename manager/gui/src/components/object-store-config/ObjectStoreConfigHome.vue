<!--
* CORTX-Halo: CORTX-Halo Management GUI.
* Copyright (c) 2022 Seagate Technology LLC and/or its Affiliates
* This program is free software: you can redistribute it and/or modify
* it under the terms of the GNU Affero General Public License as published
* by the Free Software Foundation, either version 3 of the License, or
* (at your option) any later version.
* This program is distributed in the hope that it will be useful,
* but WITHOUT ANY WARRANTY; without even the implied warranty of
* MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
* GNU Affero General Public License for more details.
* You should have received a copy of the GNU Affero General Public License
* along with this program. If not, see <https://www.gnu.org/licenses/>.
* For any questions about this software or licensing,
* please email opensource@seagate.com.
-->
<template>
  <v-btn
    elevation="1"
    color="primary"
    @click="$router.push({ name: 'tenant' })"
  >Go To Tenant</v-btn>
</template>
<script lang="ts">

import { Component, Vue, Prop, Watch } from "vue-property-decorator";


@Component({
  name: "ObjectStoreConfigHome",
  components: {},
})
export default class ObjectStoreConfigHome extends Vue {

}
</script>
<style lang="scss" scoped></style>
