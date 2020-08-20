<template>
  <div>
    <Navigation logoURL="/img/logo.png"/>
    <Content
      id="home"
      imgURL="https://images.pexels.com/photos/326569/pexels-photo-326569.jpeg?cs=srgb&dl=pexels-pixabay-326569.jpg&fm=jpg"
      name="I'm Francis Lee"
      job="Service Delivery Manager | Technical Project Manager | Data Analysts"
    />
    <Portfolio id="portfolio">
      <template v-slot:project>
        <Project
          imgURL="https://images.pexels.com/photos/3781895/pexels-photo-3781895.jpeg?cs=srgb&dl=pexels-andrea-piacquadio-3781895.jpg&fm=jpg"
          linkURL="https://gifthub.com"
          name="Service Delivery Management"
          description="Experienced Service Delivery Manager"
        />
        <Project
          imgURL="https://images.pexels.com/photos/372787/pexels-photo-372787.jpeg?cs=srgb&dl=pexels-pixabay-372787.jpg&fm=jpg"
          linkURL="https://github.com"
          name="Technical Project Management"
          description="Description"
        />
        <Project
          imgURL="https://images.pexels.com/photos/3183145/pexels-photo-3183145.jpeg?cs=srgb&dl=pexels-fauxels-3183145.jpg&fm=jpg"
          linkURL="https://datastudio.google.com/u/2/reporting/1d7d2323-10b0-46c0-bce1-36347db45a10/page/FtqbB"
          name="Data Analysis"
          description="Turn Unstructured Data Cave into Gold Mine"
        />
      </template>
    </Portfolio>
    <About
      id="Strength"
        profileImgURL_1="https://images.pexels.com/photos/1000445/pexels-photo-1000445.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
        profileHeader1="MORE THAN"
        profileHeader1_2="LEADERSHIP"
        profileDescription1="The job of a manager is to support his or her staff, not vice versa, and that begins by being among them.~ Bill Hewlett"
        profileImgURL_2="https://images.pexels.com/photos/3183156/pexels-photo-3183156.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
        profileHeader2="MORE THAN"
        profileHeader2_2="ANALYTIC"
        profileDescription2="Strong problem solving with Analytic Ascendancy Model"
      />
    <Contact id="contact" email="chinhoon.lee@gmail.com" phone="+6012 2841288"/>
    <Footer/>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "Portfolio of Francis"
    };
  }
};
</script>
