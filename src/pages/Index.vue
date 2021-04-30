<template>
  <Layout>

    <div class="row">
      <div class="col-md-4">
        <h1 class="display-4 serif-font-face">We develop, scale, and market online businesses</h1>
        <p class="font-big-1">With the most strategic eCommerce, website/app development, and digital marketing services, we help businesses to shift their gears towards a successful future</p>
        <p class="font-big-1">Also, our products- ERP (Enterprise Resource Planning) and POS (Point Of Sale) help businesses to reach new pinnacles without any pain</p>
        <p class="font-big-1"><a href="mailto:business@gothec.com" class="text-dark font-weight-bold"><u>business@gothec.com</u></a></p>
      </div>
      <div class="col-md-8">
        <Carousel :slides="slides" />
      </div>
    </div>
    <div class="p-5 bg-light my-3">
      <h1 class="serif-font-face">"We are a result-oriented firm that constantly strives forward to help every online business outshine and influence its audience. We have brought together a diverse range of products and services under one roof to provide 360-degree assistance.</h1>
    </div>

  </Layout>
</template>

<script>
    import Carousel from "../components/home/Carousel";
    export default {
        components: {Carousel},
        metaInfo: {
            title: 'Home'
        },
        data() {
            return {
                slides: [
                    {
                        type: 'Development',
                        title: 'eCommerce solutions',
                        src: "https://source.unsplash.com/random/800x900/?HTML",
                        description: "Start on the right foot with enthusiastic experts and get an ideal online store on any preferred framework such as Magento, Shopify, Shopware, WordPress, BigCommerce, Prestashop,  Opencart, and Django."
                    },
                    {
                        type: 'Design',
                        title: 'Website and App development',
                        src: "https://source.unsplash.com/random/800x900/?interface",
                        description: "Get truly mesmerizing websites based on global leading technologies and frameworks such as React.js, Vue.js, Angular, .Net, PHP , Spring and many more."
                    },
                    {
                        type: 'Marketing',
                        title: 'Update Digital marketing services New Feature',
                        src: "https://source.unsplash.com/random/800x900/?code",
                        description: "Get the traction your website deserves and produce high-quality sales with improved ROI. Our exceptional SEO, SEM, and SMM along with Content marketing solutions have helped many businesses achieve greater milestones over the years"
                    },
                    {
                        type: 'Our Product',
                        title: 'POS (Point Of Sale)',
                        src: "https://source.unsplash.com/random/800x900/?javascript",
                        description: "Get a future-proof business by deploying the use of versatile retail POS in your brick-and-mortar store."
                    },
                ]
            }
        }
    }
</script>

<style>
  .home-links a {
    margin-right: 1rem;
  }
</style>