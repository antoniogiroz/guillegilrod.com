<script setup lang="ts">
import { appDescription } from '~/constants'
</script>

<template>
  <div class="">
    <div class="px-6 py-24 lg:px-8 sm:px-6 sm:py-32">
      <div class="mx-auto max-w-2xl flex flex-col items-center gap-6 text-center">
        <img
          src="/images/guillemogil.jpg"
          alt="Guillemo Gil`s photo"
          width="240px"
          height="240px"
          class="mb-4 h-180px w-180px rounded-full object-cover lg:h-240px lg:w-240px md:h-200px md:w-200px"
        >
        <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl dark:text-white">
          {{ appDescription }}
        </h2>
        <p class="mx-auto max-w-xl text-lg leading-8 text-gray-600 dark:text-gray-300">
          I am a FPGA Engineer with 4+ years of experience seeking for a
          challenging position that allows me to expand my knowledge and make
          valueable contributions. Proficient in various technologies
          including VHDL and SystemVerilog, I have worked with cutting-edge
          architectures such as UltraScale+ and RFSoC. Fueled by my passion
          for the embedded world and electronics, I am committed to continuous
          learning and growth to achieve my professional and personal
          objectives.
        </p>
      </div>

      <div class="mt-8 text-center lg:mt-28">
        <h3 class="text-sm uppercase text-gray-500">
          Tech Skills
        </h3>
        <div class="mt-8 flex flex-wrap items-center justify-center gap-8">
          <span>VHDL</span>
          <span>Digital Design</span>
          <span>Vivado / Vitis</span>
          <span>FPGA</span>
          <span>Embedded C</span>
          <span>Xilinx MPSoC</span>
          <span>Xilinx UltraScale+</span>
          <span>Microprocessors</span>
        </div>
      </div>
    </div>
  </div>
</template>
