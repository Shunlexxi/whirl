<script setup lang="ts">

import { ref } from 'vue'

const asset_image = ref("/NFT.png")
const asset_name = ref("Dark Knight OSX 420")
const time = ref("9 Sept 23")
const status = ref("Ongoing")
const source_chain = ref("PEGO")
const destination_chain = ref("Polygon")



</script>

<template>
  <div class="transaction_container">
    <h3>Transactions</h3>

    <table class="table_container">

      <tr class="table_header">
        <th>Bridged Assest</th>
        <th>Time Created</th>
        <th>Status</th>
        <th>Source Chain</th>
        <th>Destination Chain</th>
      </tr>

      <tr class="rows">
        <td>
          <div class="assest_desc">
            <img :src="asset_image" alt="NFT" class="assest_image" />
            <div>
              <p>{{ asset_name }}</p>
              <p>4420</p>
            </div>
          </div>
        </td>

        <td>{{ time }}</td>
        <td>{{ status }}</td>
        <td>{{ source_chain }}</td>
        <td>{{ destination_chain }}</td>
      </tr>

      <tr class="rows">
        <td>
          <div class="assest_desc">
            <img :src="asset_image" alt="NFT" class="assest_image" />
            <div>
              <p>{{ asset_name }}</p>
              <p>4420</p>
            </div>
          </div>
        </td>

        <td>{{ time }}</td>
        <td>{{ status }}</td>
        <td>{{ source_chain }}</td>
        <td>{{ destination_chain }}</td>
      </tr>

      <tr class="rows">
        <td>
          <div class="assest_desc">
            <img :src="asset_image" alt="NFT" class="assest_image" />
            <div>
              <p>{{ asset_name }}</p>
              <p>4420</p>
            </div>
          </div>
        </td>

        <td>{{ time }}</td>
        <td>{{ status }}</td>
        <td>{{ source_chain }}</td>
        <td>{{ destination_chain }}</td>
      </tr>

      <tr class="rows">
        <td>
          <div class="assest_desc">
            <img :src="asset_image" alt="NFT" class="assest_image" />
            <div>
              <p>{{ asset_name }}</p>
              <p>4420</p>
            </div>
          </div>
        </td>

        <td>{{ time }}</td>
        <td>{{ status }}</td>
        <td>{{ source_chain }}</td>
        <td>{{ destination_chain }}</td>
      </tr>

      <tr class="rows">
        <td>
          <div class="assest_desc">
            <img :src="asset_image" alt="NFT" class="assest_image" />
            <div>
              <p>{{ asset_name }}</p>
              <p>4420</p>
            </div>
          </div>
        </td>

        <td>{{ time }}</td>
        <td>{{ status }}</td>
        <td>{{ source_chain }}</td>
        <td>{{ destination_chain }}</td>
      </tr>

    </table>


  </div>
</template>

<style scoped>
header {
  width: 1440px;
  max-width: 90%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 90px;
}

#logo {
  height: 34px;
}

#header-list {
  display: flex;
  list-style-type: none;
  gap: 60px;
}


#header-opts {
  display: flex;
  gap: 20px;
}

.navigation {
  width: 800px;
}

a {
  text-decoration: none;
  color: white;
}

h3 {
  font-size: 1em;
  line-height: 1.1;
  margin-bottom: 2%;
  font-weight: 400;
}







.transaction_container {
  width: 100%;
  height: 689px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.table_container {
  background-color: #050b17;
  width: 80%;
  border: 2px solid #091121;
  border-radius: 10px;
  text-align: center;

}


.table_header {
  background-color: #04070c;
  height: 74px;
}

.table_header th {
  font-weight: 200;
  border: none;
}

.rows td {
  height: 102px;
  border-bottom: 2px solid #000;
  padding: 0px 30px;
}

.assest_desc {
  display: flex;
  gap: 20px;
}

.assest_image {
  /* check width */
  width: 44px;
}
</style>
