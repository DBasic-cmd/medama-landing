<script setup>
// import { RouterLink } from 'vue-router';
import Card from '@/components/Card.vue';
</script>

<template>
  <section class="py-4 bg-blue-300" id="service">
    <div class="container-xl lg:container m-auto">
        <h1 class="text-6xl text-center font-bold my-4">Services</h1>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-4 p-4 rounded-lg">
        <Card>
          <h2 class="text-2xl font-bold">Lab Management</h2>
          <p class="mt-2 mb-4">
            Medama ensures accurate and efficient lab operations by enabling the automation of test scheduling,
             sample tracking, and results reporting. The platform simplifies communication
             between laboratory technicians, doctors, and patients, reducing delays and improving diagnostic accuracy.
          </p>

        </Card>
        <Card bg="bg-slate-100">
          <h2 class="text-2xl font-bold">Doctor and Nurse Coordination</h2>
          <p class="mt-2 mb-4">
            Medama provides tools that facilitate effective coordination between doctors and nurses.
             From patient records to treatment plans and shift schedules, the system ensures healthcare
              providers have real-time
             access to critical information, enabling faster and more informed decision-making.
          </p>

        </Card>

        <Card bg="bg-slate-100">
          <h2 class="text-2xl font-bold">Pharmacy Integration</h2>
          <p class="mt-2 mb-4">
            The pharmacy module of Medama streamlines inventory management, prescription processing,
             and medication dispensation. By integrating with other departments,
             such as the lab and finance, it ensures accuracy in billing and reduces the chances of medication errors.
          </p>

        </Card>

        <Card bg="bg-slate-100">
          <h2 class="text-2xl font-bold">Finance and Billing</h2>
          <p class="mt-2 mb-4">
            Medama's finance module is designed to handle all aspects of hospital billing, 
            from patient invoices to insurance claims. It offers
             transparency and precision, helping hospitals manage their finances effectively
              and ensure compliance with regulatory standards.
          </p>

        </Card>

      </div>
    </div>
  </section>
</template>