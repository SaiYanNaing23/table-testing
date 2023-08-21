<template>
<div>
  <el-container>
    <el-row>
      <el-col :span="8">
        <h1>Hello World</h1>
      </el-col>
      <el-col :span="16">
        <el-table
        stripe
        ref="multipleTable"
    :data="tableData"
    style="width: 100%"
    @selection-change="handleSelectionChange"
    >
        <el-table-column
      type="selection"
      width="55">
    </el-table-column>
    <el-table-column
      fixed
      prop="date"
      label="Date"
      width="200">
      <!-- <template slot-scope="scope">{{ scope.row.date }}</template> -->
      <template>

        <el-checkbox></el-checkbox>
        <el-button type="text" size="small">Edit</el-button>
      </template>
    </el-table-column>
    <el-table-column
      prop="name"
      label="Name"
      width="120">
    </el-table-column>
    <el-table-column
      prop="state"
      label="State"
      width="120">
    </el-table-column>
    <el-table-column
      prop="city"
      label="City"
      width="120">
    </el-table-column>
    <el-table-column
      prop="address"
      label="Address"
      width="300">
    </el-table-column>
        <el-table-column
      prop="address"
      label="Address"
      width="300">
    </el-table-column>
        <el-table-column
      prop="address"
      label="Address"
      width="300">
    </el-table-column>
        <el-table-column
      prop="address"
      label="Address"
      width="300">
    </el-table-column>
    <el-table-column
      prop="zip"
      label="Zip"
      width="120">
    </el-table-column>
    <!-- <el-table-column
      fixed="right"
      label="Operations"
      width="120">
    </el-table-column> -->
  </el-table>
      </el-col>
    </el-row>
  </el-container>
 <el-table
    :data="tableData"
    style="width: 100%">
    <el-table-column
      prop="date"
      label="Sai Yan Naing"
      width="150">
    </el-table-column>
    <!-- <el-table-column label="Delivery Info"> -->
      <el-table-column
        prop="name"
        label="Name"
        width="120">
      </el-table-column>
      <!-- <el-table-column label="Address Info"> -->
        <el-table-column
          prop="state"
          label="State"
          width="120">
        </el-table-column>
        <el-table-column
          prop="city"
          label="City"
          width="120">
        </el-table-column>
        <el-table-column
          prop="address"
          label="Address"
          width="300">
        </el-table-column>
        <el-table-column
          prop="zip"
          label="Zip"
          width="120">
        </el-table-column>
                <el-table-column
          prop="zip"
          label="Zip"
          width="120">
        </el-table-column>
                <el-table-column
          prop="zip"
          label="Zip"
          width="120">
        </el-table-column>
                <el-table-column
          prop="zip"
          label="Zip"
          width="120">
        </el-table-column>        <el-table-column
          prop="zip"
          label="Zip"
          width="120">
        </el-table-column>        <el-table-column
          prop="zip"
          label="Zip"
          width="120">
        </el-table-column>        <el-table-column
          prop="zip"
          label="Zip"
          width="120">
        </el-table-column>        <el-table-column
          prop="zip"
          label="Zip"
          width="120">
        </el-table-column>        <el-table-column
          prop="zip"
          label="Zip"
          width="120">
        </el-table-column>        <el-table-column
          prop="zip"
          label="Zip"
          width="120">
        </el-table-column>
      <!-- </el-table-column> -->
    <!-- </el-table-column> -->
  </el-table>

  
</div>

</template>

<script>
export default {
  data() {
      return {
        tableData: [{
          date: 'Sai Yan Naing',
          name: 'Jerry',
          state: 'California',
          city: 'Los Angeles',
          address: 'No. 189, Grove St, Los Angeles',
          zip: 'CA 90036'
        }, {
          date: '2016-05-02',
          name: 'Tom',
          state: 'California',
          city: 'Los Angeles',
          address: 'No. 189, Grove St, Los Angeles',
          zip: 'CA 90036'
        }, {
          date: '2016-05-04',
          name: 'Tom',
          state: 'California',
          city: 'Los Angeles',
          address: 'No. 189, Grove St, Los Angeles',
          zip: 'CA 90036'
        }, {
          date: '2016-05-01',
          name: 'Tom',
          state: 'California',
          city: 'Los Angeles',
          address: 'No. 189, Grove St, Los Angeles',
          zip: 'CA 90036'
        }, {
          date: '2016-05-08',
          name: 'Tom',
          state: 'California',
          city: 'Los Angeles',
          address: 'No. 189, Grove St, Los Angeles',
          zip: 'CA 90036'
        }, {
          date: '2016-05-06',
          name: 'Tom',
          state: 'California',
          city: 'Los Angeles',
          address: 'No. 189, Grove St, Los Angeles',
          zip: 'CA 90036'
        }, {
          date: '2016-05-07',
          name: 'Tom',
          state: 'California',
          city: 'Los Angeles',
          address: 'No. 189, Grove St, Los Angeles',
          zip: 'CA 90036'
        },
        {
          date: '2016-05-07',
          name: 'Tom',
          state: 'California',
          city: 'Los Angeles',
          address: 'No. 189, Grove St, Los Angeles',
          zip: 'CA 90036'
        }]
      }
    },
    methods: {
      handleClick() {
        console.log('click');
      }
    },
}
</script>

