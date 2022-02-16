<script setup>
import FooterComponentVue from "../components/FooterComponent.vue";
import HeaderCompoentVue from "../components/HeaderCompoent.vue";
import HeroSection from "../components/HeroSectionComponent.vue";
import SliderComponenent from "../components/SliderComponenent.vue";
import FirstSectionComponent from "../components/FirstSectionComponent.vue";
import SectionTwoComponent from "../components/SectionTwoComponent.vue";
import SectionThreeComponent from "../components/SectionThreeComponent.vue";
import SectionFourComponent from "../components/SectionFourComponent.vue";
import SectionFiveComponent from "../components/SectionFiveComponent.vue";
import SectionSixComponent from "../components/SectionSixComponent.vue";
import Section7Component from "../components/Section7Component.vue";
import Section8Component from "../components/Section8Component.vue";
import Section9Component from "../components/Section9Component.vue";
</script>

<template>
  <main>
    <HeaderCompoentVue />
    <main class="body-container-wrapper">
      <HeroSection />
      <div class="container-fluid body-container">
        <div class="row-fluid-wrapper">
          <div class="row-fluid">
            <div
              class="span12 widget-span widget-type-cell"
              style=""
              data-widget-type="cell"
              data-x="0"
              data-w="12"
            >
              <SliderComponenent />
              <FirstSectionComponent />
              <SectionTwoComponent />
              <SectionThreeComponent />
              <SectionFourComponent />
              <SectionFiveComponent />
              <SectionSixComponent />
              <Section7Component />
              <Section8Component />
              <Section9Component />
            </div>
          </div>
        </div>
      </div>
    </main>
    <FooterComponentVue />
  </main>
</template>
