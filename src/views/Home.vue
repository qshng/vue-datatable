<template>
  <div>
    <DataTable />
    <PropertyCard />
  </div>
</template>

<script>
import DataTable from '@/components/DataTable'
import PropertyCard from '@/components/PropertyCard'

export default {
  name: 'Home',
  components: { DataTable, PropertyCard },
  data() {
    return {
      //
    }
  }
}
</script>
