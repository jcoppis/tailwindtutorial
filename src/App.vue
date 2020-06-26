<template>
  <Navbar />
</template>

<script>
// import PropertyCard from './components/PropertyCard';
import Navbar from './components/Navbar';

export default {
  name: 'App',
  components: {
    // PropertyCard,
    Navbar,
  },
  data: () => ({
    property: {
      imageUrl: 'https://images.unsplash.com/photo-1580587771525-78b9dba3b914?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=667&q=80',
      imageAlt: 'lalala',
      beds: 3,
      baths: 2,
      title: 'Modern home in city center',
      priceInCents: 190000,
      formattedPrice: '$1,900.00',
      reviewCount: 34,
      rating: 4,
    }
  })
}
</script>