<template>
  <div class="container px-6 mx-auto mb-16">
      <div class="flex flex-wrap -mx-6">
          <div class="flex-none w-full px-6 mb-8 lg:w-80">
              <div class="overflow-hidden bg-white border rounded">
                    <div class="border-b">
                        <a href="#!" class="block px-4 py-3 font-semibold text-black no-underline border-l-2 border-green-500 hover:bg-gray-200">General</a> 
                    </div>
                    <div class="border-b">
                        <a href="#!" class="block py-3 pl-6 pr-4 text-sm text-black no-underline bg-gray-100 hover:bg-gray-200">Site details</a> 
                    </div>
                    <div class="border-b">
                        <a href="#!" class="block py-3 pl-6 pr-4 text-sm text-gray-500 no-underline bg-gray-100 hover:bg-gray-200">Status badges</a> 
                    </div>
                    <div class="border-b">
                        <a href="#!" class="block py-3 pl-6 pr-4 text-sm text-gray-500 no-underline bg-gray-100 hover:bg-gray-200">Site members</a> 
                    </div>
                    <div class="border-b">
                        <a href="#!" class="block py-3 pl-6 pr-4 text-sm text-gray-500 no-underline bg-gray-100 hover:bg-gray-200">Danger zone</a> 
                    </div>
                    <div class="border-b">
                        <a href="#!" class="block px-4 py-3 text-gray-500 no-underline border-l-2 border-transparent hover:bg-gray-200">Build & deploy</a> 
                    </div>
                    <div class="border-b">
                        <a href="#!" class="block px-4 py-3 text-gray-500 no-underline border-l-2 border-transparent hover:bg-gray-200">Domain management</a> 
                    </div>
                    <div class="border-b">
                        <a href="#!" class="block px-4 py-3 text-gray-500 no-underline border-l-2 border-transparent hover:bg-gray-200">Analytics</a> 
                    </div>
                    <div class="border-b">
                        <a href="#!" class="block px-4 py-3 text-gray-500 no-underline border-l-2 border-transparent hover:bg-gray-200">Functions</a> 
                    </div>
                    <div class="border-b">
                        <a href="#!" class="block px-4 py-3 text-gray-500 no-underline border-l-2 border-transparent hover:bg-gray-200">Identity</a> 
                    </div>
                    <div class="border-b">
                        <a href="#!" class="block px-4 py-3 text-gray-500 no-underline border-l-2 border-transparent hover:bg-gray-200">Forms</a> 
                    </div>
                    <div class="border-b">
                        <a href="#!" class="block px-4 py-3 text-gray-500 no-underline border-l-2 border-transparent hover:bg-gray-200">Large Media</a> 
                    </div>
                    <div class="border-b">
                        <a href="#!" class="block px-4 py-3 text-gray-500 no-underline border-l-2 border-transparent hover:bg-gray-200">Access control</a> 
                    </div>
                    <div class="border-b">
                        <a href="#!" class="block px-4 py-3 text-gray-500 no-underline border-l-2 border-transparent hover:bg-gray-200">General site settings</a> 
                    </div>
              </div>
          </div>
          <div class="flex-1 px-6">
                <div class="mb-6">
                    <h2 class="mb-2 text-2xl font-semibold">Site Details</h2>
                    <p class="text-gray-500">General information about your site</p>
                </div>
                <div class="p-6 bg-white rounded-lg shadow ">
                    <h3 class="pb-3 mb-2 text-xl font-semibold border-b-2 border-gray-50">Site information</h3>
                    <div class="mb-6 -mx-6">    
                        <table class="w-full">
                            <tr>
                                <td class="w-1/4 px-6 py-2">
                                    Site name:
                                </td>
                                <td class="w-3/4 px-6 py-2 font-semibold text-black">
                                    <a href="#!" class="font-semibold text-black no-underline">zenithintschool</a>
                                </td>
                            </tr>
                            <tr>
                                <td class="w-1/4 px-6 py-2 bg-gray-100">
                                    Owner:
                                </td>
                                <td class="w-3/4 px-6 py-2 font-semibold text-black bg-gray-100">
                                    <a href="#!" class="font-semibold text-black no-underline">Kofi Teddy's team</a>
                                </td>
                            </tr>
                            <tr>
                                <td class="w-1/4 px-6 py-2">
                                    API ID:
                                </td>
                                <td class="w-3/4 px-6 py-2 font-semibold text-black">
                                    <a href="#!" class="font-semibold text-black no-underline">97766da0-7a55-4f7d-ac59-5dfb6de1b1e4</a>
                                </td>
                            </tr>
                            <tr>
                                <td class="w-1/4 px-6 py-2 bg-gray-100">
                                    Created:
                                </td>
                                <td class="w-3/4 px-6 py-2 font-semibold text-black bg-gray-100">
                                    <a href="#!" class="font-semibold text-black no-underline">Jun 16 at 2:18 AM</a>
                                </td>
                            </tr>
                            <tr>
                                <td class="w-1/4 px-6 py-2">
                                    Last update:
                                </td>
                                <td class="w-3/4 px-6 text-black py-2font-semibold">
                                    <a href="#!" class="font-semibold text-black no-underline">Jun 16 at 2:19 AM</a>
                                </td>
                            </tr>
                        </table>
                    </div>
                    <button type="button" class="px-4 py-2 font-normal text-black bg-gray-200 border rounded shadow hover:bg-green-50 hover:border-green-50 hover:text-green-900">Change Site Name</button>
                </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: 'ColSection'
}
</script>

<style>

</style>