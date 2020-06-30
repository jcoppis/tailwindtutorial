<template>
  <div id="app" class="antialiased text-gray-900">
    <div class="bg-gray-800 min-h-screen py-32 px-6">
    <AccountDropdown />  
    </div>
  </div>
</template>

<script>
// import PropertyCard from './components/PropertyCard';
// import Navbar from './components/Navbar';
import AccountDropdown from './components/AccountDropdown';

export default {
  name: 'App',
  components: {
    // PropertyCard,
    // Navbar,
    AccountDropdown
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