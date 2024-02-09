<script >
import Nav from '~/components/Nav.vue'
</script>

<template>
  <div>
    <Nav />
    <div class="container mx-auto tex-center m-3">
      <h1 class="text-center">Explore Typescript and Javascript libraries for instant messaging</h1>
        <table class="mx-auto table-auto border border-slate-400 border-spacing-6 m-3" >
        <thead>
          <tr>
            <th class="border border-slate-300 p-4">Name of the libraries</th>
            <th class="border border-slate-300 p-4">Github Link</th>
            <th class="border border-slate-300 p-4">Website Link</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="border border-slate-300 p-4">Sendbird</td>
            <td class="border border-slate-300 p-4">https://github.com/sendbird</td>
            <td class="border border-slate-300 p-4">https://sendbird.com</td>
          </tr>
          <tr>
            <td class="border border-slate-300 p-4">OpenTalk</td>
            <td class="border border-slate-300 p-4">https://github.com/opentok</td>
            <td class="border border-slate-300 p-4">https://www.vonage.com/communications-apis/video/</td>
          </tr>
        </tbody>
      </table>
       
    </div>
  </div>
</template>