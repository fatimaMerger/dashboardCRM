<script>
import InputUI from './InputUI.vue';

export default {
    name: 'Leads',
};
</script>
<template>
    <div class="flex min-h-screen">
        <aside
            class="w-64 bg-gradient-to-b from-[#eaabf0]/20 to-[#4623e9]/10 flex flex-col justify-between h-screen sticky top-0">
            <div class="flex items-center p-6 pb-4 border-b border-gray-300 h-[80px]">
                <div class="w-10 h-10 bg-[#9B51E0] rounded-md flex items-center justify-center mr-3">
                    <span class="text-white font-poppins text-xl font-bold">C</span>
                </div>
                <div>
                    <h1 class="text-lg font-poppins font-bold text-gray-900 leading-tight">
                        CRM
                    </h1>
                    <p class="text-sm font-poppins text-gray-500 leading-tight">
                        Administration
                    </p>
                </div>
            </div>
            <div class="flex-1 overflow-y-auto custom-scrollbar">
                <nav class="mt-4">
                    <ul class="space-y-1">
                        <li class="mb-2">
                            <a href="#"
                                class="flex items-center mx-4 py-2 px-4 text-gray-700 hover:bg-white rounded-lg transition-colors rounded-l-md font-poppins font-medium">
                                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24"
                                    fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                    stroke-linejoin="round"
                                    class="feather feather-layout-dashboard mr-3 text-[#242424]">
                                    <rect x="3" y="3" width="18" height="18" rx="2" ry="2" />
                                    <line x1="3" y1="9" x2="21" y2="9" />
                                    <line x1="9" y1="21" x2="9" y2="9" />
                                </svg>

                                Dashboard
                            </a>
                        </li>

                        <li class="mb-2">
                            <a href="#"
                                class="flex items-center mx-4 py-2 px-4 bg-white text-[#9B51E0] rounded-lg font-poppins font-semibold">
                                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24"
                                    fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                    stroke-linejoin="round" class="feather feather-bell-ring mr-3 text-purple-500">
                                    <path d="M18 8A6 6 0 0 0 6 8c0 7-3 9-3 9h18s-3-2-3-9" />
                                    <path d="M13.73 21a2 2 0 0 1-3.46 0" />
                                </svg>
                                Notifications
                            </a>
                        </li>

                        <li class="mb-2">
                            <a href="#"
                                class="flex items-center mx-4 py-2 px-4 text-gray-700 hover:bg-white rounded-lg transition-colors rounded-l-md font-poppins font-medium">
                                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24"
                                    fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                    stroke-linejoin="round" class="feather feather-users mr-3 text-[#242424]">
                                    <path d="M16 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2" />
                                    <circle cx="8.5" cy="7" r="4" />
                                    <path d="M20 8v6M23 11h-6" />
                                </svg>
                                Leads
                            </a>
                        </li>

                        <li class="mb-2">
                            <a href="#"
                                class="flex items-center mx-4 py-2 px-4 text-gray-700 hover:bg-white rounded-lg transition-colors rounded-l-md font-poppins font-medium">
                                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24"
                                    fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                    stroke-linejoin="round" class="feather feather-zap mr-3 text-[#242424]">
                                    <polygon points="13 2 3 14 12 14 11 22 21 10 12 10 13 2" />
                                </svg>
                                Deals
                            </a>
                        </li>

                        <li class="mb-2">
                            <a href="#"
                                class="flex items-center mx-4 py-2 px-4 text-gray-700 hover:bg-white rounded-lg transition-colors rounded-l-md font-poppins font-medium">
                                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24"
                                    fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                    stroke-linejoin="round" class="feather feather-user mr-3 text-[#242424]">
                                    <path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2" />
                                    <circle cx="12" cy="7" r="4" />
                                </svg>
                                Contacts
                            </a>
                        </li>

                        <li class="mb-2">
                            <a href="#"
                                class="flex items-center mx-4 py-2 px-4 text-gray-700 hover:bg-white rounded-lg transition-colors rounded-l-md font-poppins font-medium">
                                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24"
                                    fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                    stroke-linejoin="round" class="feather feather-briefcase mr-3 text-[#242424]">
                                    <rect x="2" y="7" width="20" height="14" rx="2" ry="2" />
                                    <path d="M16 21V5a2 2 0 0 0-2-2H8a2 2 0 0 0-2 2v16" />
                                </svg>
                                Organization
                            </a>
                        </li>

                        <li class="mb-2">
                            <a href="#"
                                class="flex items-center mx-4 py-2 px-4 text-gray-700 hover:bg-white rounded-lg transition-colors rounded-l-md font-poppins font-medium">
                                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24"
                                    fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                    stroke-linejoin="round" class="feather feather-file-text mr-3 text-[#242424]">
                                    <path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z" />
                                    <polyline points="14 2 14 8 20 8" />
                                    <line x1="16" y1="13" x2="8" y2="13" />
                                    <line x1="16" y1="17" x2="8" y2="17" />
                                    <polyline points="10 9 9 9 8 9" />
                                </svg>
                                Notes
                            </a>
                        </li>

                        <li class="mb-2">
                            <a href="#"
                                class="flex items-center mx-4 py-2 px-4 text-gray-700 hover:bg-white rounded-lg transition-colors rounded-l-md font-poppins font-medium">
                                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24"
                                    fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                    stroke-linejoin="round" class="feather feather-check-square mr-3 text-[#242424]">
                                    <polyline points="9 11 12 14 22 4" />
                                    <path d="M21 12v7a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h11" />
                                </svg>
                                Tasks
                            </a>
                        </li>

                        <li class="mb-2">
                            <a href="#"
                                class="flex items-center mx-4 py-2 px-4 text-gray-700 hover:bg-white rounded-lg transition-colors rounded-l-md font-poppins font-medium">
                                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24"
                                    fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                    stroke-linejoin="round" class="feather feather-heart mr-3 text-[#242424]">
                                    <path
                                        d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z" />
                                </svg>
                                Donor
                            </a>
                        </li>

                        <li class="mb-2">
                            <a href="#"
                                class="flex items-center mx-4 py-2 px-4 text-gray-700 hover:bg-white rounded-lg transition-colors rounded-l-md font-poppins font-medium">
                                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24"
                                    fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                    stroke-linejoin="round" class="feather feather-gift mr-3 text-[#242424]">
                                    <polyline points="20 12 20 22 4 22 4 12" />
                                    <path d="M2 7h20v5H2z" />
                                    <path d="M12 22V7" />
                                    <path d="M12 7H7.5a2.5 2.5 0 0 1 0-5C11.5 5 12 7 12 7z" />
                                    <path d="M12 7h4.5a2.5 2.5 0 0 0 0-5C12.5 5 12 7 12 7z" />
                                </svg>
                                Donation
                            </a>
                        </li>

                        <li class="mb-2">
                            <a href="#"
                                class="flex items-center mx-4 py-2 px-4 text-gray-700 hover:bg-white rounded-lg transition-colors rounded-l-md font-poppins font-medium">
                                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24"
                                    fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                    stroke-linejoin="round" class="feather feather-phone mr-3 text-[#242424]">
                                    <path
                                        d="M22 16.92v3a2 2 0 0 1-2.18 2.02A19.5 19.5 0 0 1 8.64 12.06c-3.15-3.15-4.88-6.19-5.91-9.28a2 2 0 0 1 2.02-2.18h3a2 2 0 0 1 2 2c0 2.22-1.3 4.2-3.23 6.13A17.56 17.56 0 0 0 12.06 17.06c1.93-1.93 3.91-3.23 6.13-3.23a2 2 0 0 1 2 2z" />
                                </svg>
                                Call Logs
                            </a>
                        </li>

                        <li class="mb-2">
                            <a href="#"
                                class="flex items-center mx-4 py-2 px-4 text-gray-700 hover:bg-white rounded-lg transition-colors rounded-l-md font-poppins font-medium">
                                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24"
                                    fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                    stroke-linejoin="round" class="feather feather-mail mr-3 text-[#242424]">
                                    <path
                                        d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z" />
                                    <polyline points="22 6 12 13 2 6" />
                                </svg>
                                Email Templates
                            </a>
                        </li>

                        <li class="mb-2">
                            <a href="#"
                                class="flex items-center mx-4 py-2 px-4 text-gray-700 hover:bg-white rounded-lg transition-colors rounded-l-md font-poppins font-medium">
                                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24"
                                    fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                    stroke-linejoin="round" class="feather feather-shield mr-3 text-[#242424]">
                                    <path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z" />
                                </svg>
                                Case Officers
                            </a>
                        </li>
                    </ul>
                </nav>
            </div>

            <div
                class="p-4 mx-4 mb-4 rounded-xl text-white overflow-hidden bg-gradient-to-l to-[#9B51E0] from-[#4623e9]">
                <h3 class="font-poppins font-semibold">Getting Started</h3>
                <p class="text-sm font-poppins mt-1">2/9 steps</p>
                <button
                    class="w-full mt-4 flex items-center justify-center py-2 bg-white bg-opacity-20 backdrop-filter backdrop-blur-sm rounded-lg font-poppins text-sm font-medium hover:bg-opacity-30 transition-colors text-[#9B51E0]">
                    Continue
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none"
                        stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                        class="feather feather-arrow-right ml-2">
                        <line x1="5" y1="12" x2="19" y2="12" />
                        <polyline points="12 5 19 12 12 19" />
                    </svg>
                </button>
            </div>
        </aside>

        <div class="flex-1 flex flex-col">
            <header
                class="fixed top-0 z-10 w-full flex items-center justify-between px-6 border-b border-gray-200 bg-white h-[80px]">
                <div>
                    <h2 class="text-2xl font-poppins font-semibold text-gray-900">
                        Notifications
                    </h2>
                    <p class="text-sm font-poppins text-gray-500 mt-1">
                        Manage your notifications here
                    </p>
                </div>

                <button
                    class="flex items-center px-4 py-2 bg-[#9B51E0] text-white rounded-lg shadow-sm hover:bg-opacity-90 transition-colors">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none"
                        stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                        class="mr-2">
                        <path d="M22 11.08V12a10 10 0 1 1-5.93-8.72" />
                        <path d="M22 4L12 14.01l-3-3" />
                    </svg>
                    <span class="font-poppins text-sm font-medium">Mark all as read</span>
                </button>
            </header>

            <main class="mt-[80px] flex-1 overflow-y-auto custom-scrollbar h-[calc(100vh-80px)]">

                <div class="flex">
                    <div class=" w-full mr-[303px]">
                        <div class="flex space-x-6 border-b border-[#DCE0E5] bg-white px-6 py-4 mb-6">
                            <a href="#"
                                class=" text-sm font-poppins  text-gray-500 hover:text-[#9B51E0] border-b-2 border-transparent hover:border-[#9B51E0] transition-colors">
                                Activity
                            </a>
                            <a href="#"
                                class=" text-sm font-poppins  text-gray-500 hover:text-[#9B51E0] border-b-2 border-transparent hover:border-[#9B51E0] transition-colors">
                                Email
                            </a>
                            <a href="#"
                                class=" text-sm font-poppins  text-gray-500 hover:text-[#9B51E0] border-b-2 border-transparent hover:border-[#9B51E0] transition-colors">
                                Comments
                            </a>
                            <a href="#"
                                class=" text-sm font-poppins  text-gray-500 hover:text-[#9B51E0] border-b-2 border-transparent hover:border-[#9B51E0] transition-colors">
                                Data
                            </a>
                            <a href="#"
                                class=" text-sm font-poppins  text-gray-500 hover:text-[#9B51E0] border-b-2 border-transparent hover:border-[#9B51E0] transition-colors">
                                Calls
                            </a>
                            <a href="#"
                                class=" text-sm font-poppins text-gray-500 hover:text-[#9B51E0] border-b-2 border-transparent hover:border-[#9B51E0] transition-colors">
                                Tasks
                            </a>
                            <a href="#"
                                class=" text-sm font-poppins text-gray-500 hover:text-[#9B51E0] border-b-2 border-transparent hover:border-[#9B51E0] transition-colors">
                                Notes
                            </a>
                            <a href="#"
                                class="relative text-sm font-poppins font-semibold text-[#9B51E0] after:content-[''] after:absolute after:top-[36px] after:left-0 after:w-full after:h-[2px] after:bg-[#9B51E0]">
                                Attachments
                            </a>
                        </div>

                        <!-- <InputUI /> -->
                        <div class="p-6 bg-white border border-gray-200 rounded-lg shadow-sm mx-6">
                            <h2 class="text-base font-semibold text-gray-800 mb-4">Person</h2>

                            <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                                <!-- Salutation -->
                                <div>
                                    <label class="block text-sm font-medium text-gray-700 mb-2">Salutation</label>
                                    <select
                                        class="w-full h-12 border border-gray-300 rounded px-3 text-sm text-gray-700 focus:outline-none focus:ring-2 focus:ring-purple-500">
                                        <option>Salutation</option>
                                    </select>
                                </div>

                                <!-- First Name -->
                                <div>
                                    <label class="block text-sm font-medium text-gray-700 mb-2">First Name</label>
                                    <input type="text" placeholder="First Name"
                                        class="w-full h-12 border border-gray-300 rounded px-3 text-sm focus:outline-none focus:ring-2 focus:ring-purple-500" />
                                </div>

                                <!-- Last Name -->
                                <div>
                                    <label class="block text-sm font-medium text-gray-700 mb-2">Last Name</label>
                                    <input type="text" placeholder="Last name"
                                        class="w-full h-12 border border-gray-300 rounded px-3 text-sm focus:outline-none focus:ring-2 focus:ring-purple-500" />
                                </div>

                                <!-- Email -->
                                <div>
                                    <label class="block text-sm font-medium text-gray-700 mb-2">Email</label>
                                    <input type="email" placeholder="Email"
                                        class="w-full h-12 border border-gray-300 rounded px-3 text-sm focus:outline-none focus:ring-2 focus:ring-purple-500" />
                                </div>

                                <!-- Mobile No -->
                                <div>
                                    <label class="block text-sm font-medium text-gray-700 mb-2">Mobile no</label>
                                    <input type="tel" placeholder="mobile no"
                                        class="w-full h-12 border border-gray-300 rounded px-3 text-sm focus:outline-none focus:ring-2 focus:ring-purple-500" />
                                </div>

                                <!-- Status -->
                                <div>
                                    <label class="block text-sm font-medium text-gray-700 mb-2">Status <span
                                            class="text-red-500">*</span></label>
                                    <select
                                        class="w-full h-12 border border-gray-300 rounded px-3 text-sm text-gray-700 focus:outline-none focus:ring-2 focus:ring-purple-500">
                                        <option>New</option>
                                    </select>
                                </div>
                            </div>
                        </div>

                        <h1 class="text-xl font-medium px-6">Attachments</h1>
                        <div
                            class="m-6 p-14 border border-gray-300 rounded-lg flex flex-col items-center justify-center text-center bg-gray-50">
                            <div
                                class="w-18 h-18 rounded-full overflow-hidden border-2 border-gray-300 bg-gray-100 flex items-center justify-center">
                                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
                                    fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                    stroke-linejoin="round"
                                    class="lucide lucide-paperclip-icon lucide-paperclip text-gray-400">
                                    <path
                                        d="m16 6-8.414 8.586a2 2 0 0 0 2.829 2.829l8.414-8.586a4 4 0 1 0-5.657-5.657l-8.379 8.551a6 6 0 1 0 8.485 8.485l8.379-8.551" />
                                </svg>
                            </div>
                            <h3 class="mt-4 text-gray-700 font-semibold">No Attachments</h3>
                            <p class="mt-1 text-sm text-gray-500">Drag and drop files here or click to browse</p>
                            <button
                                class="mt-6 flex items-center px-6 py-2 bg-[#9B51E0] text-white rounded-lg shadow-sm hover:bg-opacity-90 transition-colors">
                                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
                                    fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                    stroke-linejoin="round" class="lucide lucide-plus-icon lucide-plus h-5 w-5 mr-2">
                                    <path d="M5 12h14" />
                                    <path d="M12 5v14" />
                                </svg>


                                Upload Attachment
                            </button>
                        </div>
                    </div>

                    <div
                        class="space-y-6 bg-white p-6  border-l border-[#DCE0E5] fixed top-[80px] right-0 w-[303px] h-[calc(100vh-80px)] overflow-y-auto custom-scrollbar">
                        <div class="flex justify-between items-center">
                            <h2 class="text-lg font-semibold text-gray-800">Lead Summary</h2>
                        </div>

                        <div class="space-y-4 text-sm text-gray-600">
                            <div>
                                <p class=" text-gray-500">Lead ID</p>
                                <p class="text-black">CRM-LEAD-2025-00006</p>
                            </div>
                            <div>
                                <p class=" text-gray-500">Lead Owner</p>
                                <div class="flex items-center gap-2">
                                    <div class="w-10 h-10 rounded-full overflow-hidden border-2 border-gray-300">
                                        <img src="https://i.pravatar.cc/100" alt="User Avatar"
                                            class="w-full h-full object-cover" />
                                    </div>
                                    <span class="text-dark font-semibold">
                                        Administrator
                                    </span>
                                    <span
                                        class="inline-flex items-center px-2 py-0.5 rounded-full text-xs font-medium bg-gray-100 text-gray-800 ml-2">
                                        Owner
                                    </span>
                                </div>

                            </div>
                            <div>
                                <p class=" text-gray-500">Organization</p>
                                <p class="text-black">TechCorp Solutions</p>
                            </div>
                            <div>
                                <p class=" text-gray-500">Industry</p>
                                <p class="text-black">Technology</p>
                            </div>
                            <div>
                                <p class=" text-gray-500">Website</p>
                                <a href="#" class="text-blue-500">www.techcorp.com</a>
                            </div>
                        </div>

                        <div class="border-t border-gray-200 pt-6 space-y-4">
                            <h3 class="font-semibold text-gray-800">Contact Person</h3>
                            <div>
                                <p class=" text-gray-500">Name</p>
                                <p class="text-black">Mr. John Smith</p>
                            </div>
                            <div>
                                <p class=" text-gray-500">Email</p>
                                <p class="text-blue-500">john.smith@techcorp.com</p>
                            </div>
                            <div>
                                <p class=" text-gray-500">Mobile</p>
                                <p class="text-black">+1 (555) 123-4567</p>
                            </div>
                        </div>

                        <button
                            class="w-full bg-[#9B51E0] text-white py-2 rounded-lg font-medium flex items-center justify-center space-x-2 hover:bg-purple-600 transition-colors gap-2">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24"
                                fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                stroke-linejoin="round" class="lucide lucide-zap-icon lucide-zap">
                                <path
                                    d="M4 14a1 1 0 0 1-.78-1.63l9.9-10.2a.5.5 0 0 1 .86.46l-1.92 6.02A1 1 0 0 0 13 10h7a1 1 0 0 1 .78 1.63l-9.9 10.2a.5.5 0 0 1-.86-.46l1.92-6.02A1 1 0 0 0 11 14z" />
                            </svg>
                            Convert to Deal
                        </button>
                    </div>



                </div>


            </main>
        </div>
    </div>
</template>
