<script>
export default {
    name: 'AdminDashboard',
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
                                class="flex items-center mx-4 py-2 px-4 bg-white text-purple-700 rounded-lg font-poppins font-semibold">
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
                class="p-4 mx-4 mb-4 rounded-xl text-white overflow-hidden bg-gradient-to-l from-[#eaabf0] to-[#4623e9]">
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
            <header class="flex items-center justify-between px-6 border-b border-gray-200 bg-white h-[80px]">
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

            <main class="p-6">
                <nav class="mb-4 bg-white rounded-lg border-[#DCE0E5] border size-fit">
                    <ul class="flex space-x-2 p-4">
                        <li>
                            <a href="#"
                                class="bg-[#9B51E0] text-white font-poppins font-medium py-2 px-4 rounded-md text-sm">All</a>
                        </li>
                        <li>
                            <a href="#"
                                class="text-gray-600 font-poppins font-medium py-2 px-4 rounded-md text-sm hover:bg-white rounded-lg">Unread</a>
                        </li>
                        <li>
                            <a href="#"
                                class="text-gray-600 font-poppins font-medium py-2 px-4 rounded-md text-sm hover:bg-white rounded-lg">Tasks</a>
                        </li>
                        <li>
                            <a href="#"
                                class="text-gray-600 font-poppins font-medium py-2 px-4 rounded-md text-sm hover:bg-white rounded-lg">Contacts</a>
                        </li>
                        <li>
                            <a href="#"
                                class="text-gray-600 font-poppins font-medium py-2 px-4 rounded-md text-sm hover:bg-white rounded-lg">System</a>
                        </li>
                    </ul>
                </nav>
                <div class="space-y-4">
                    <div
                        class="bg-white rounded-md shadow-sm border-l-4 border-cyan-500 h-[104px] p-4 flex items-center">
                        <div
                            class="w-10 h-10 rounded-full bg-cyan-100 text-cyan-600 flex items-center justify-center mr-3">
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24"
                                fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                stroke-linejoin="round" class="feather feather-check-circle">
                                <path d="M22 11.08V12a10 10 0 1 1-5.93-8.88"></path>
                                <polyline points="22 4 12 14.01 9 11.01"></polyline>
                            </svg>
                        </div>
                        <div class="flex-1">
                            <h6 class="font-semibold text-gray-800 text-lg">
                                Task completed: Follow up with John Doe
                            </h6>
                            <p class="text-gray-500 text-sm">
                                Your scheduled follow-up task has been marked as completed.
                            </p>
                        </div>
                        <div class="flex flex-col items-end ml-2">
                            <span
                                class="bg-cyan-100 text-cyan-600 text-sm font-semibold px-3 py-1 rounded-full">Completed</span>
                            <span class="text-gray-400 text-sm mt-2">1 hour ago</span>
                        </div>
                    </div>

                    <div
                        class="bg-white rounded-md shadow-sm border-l-4 border-pink-500 h-[104px] p-4 flex items-center">
                        <div
                            class="w-10 h-10 rounded-full bg-pink-100 text-pink-600 flex items-center justify-center mr-3">
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24"
                                fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                stroke-linejoin="round" class="feather feather-user-plus">
                                <path d="M16 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"></path>
                                <circle cx="8.5" cy="7" r="4"></circle>
                                <line x1="20" y1="8" x2="20" y2="14"></line>
                                <line x1="23" y1="11" x2="17" y2="11"></line>
                            </svg>
                        </div>
                        <div class="flex-1">
                            <h6 class="font-semibold text-gray-800 text-lg">
                                New lead assigned: Sarah Malik
                            </h6>
                            <p class="text-gray-500 text-sm">
                                A new lead from the marketing campaign has been assigned to
                                your pipeline.
                            </p>
                        </div>
                        <div class="flex flex-col items-end ml-2">
                            <span
                                class="bg-pink-100 text-pink-600 text-sm font-semibold px-3 py-1 rounded-full">Read</span>
                            <span class="text-gray-400 text-sm mt-2">5 mins ago</span>
                        </div>
                    </div>

                    <div
                        class="bg-white rounded-md shadow-sm border-l-4 border-cyan-500 h-[104px] p-4 flex items-center">
                        <div
                            class="w-10 h-10 rounded-full bg-cyan-100 text-cyan-600 flex items-center justify-center mr-3">
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24"
                                fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                stroke-linejoin="round" class="feather feather-check-circle">
                                <path d="M22 11.08V12a10 10 0 1 1-5.93-8.88"></path>
                                <polyline points="22 4 12 14.01 9 11.01"></polyline>
                            </svg>
                        </div>
                        <div class="flex-1">
                            <h6 class="font-semibold text-gray-800 text-lg">
                                Task completed: Follow up with John Doe
                            </h6>
                            <p class="text-gray-500 text-sm">
                                Your scheduled follow-up task has been marked as completed.
                            </p>
                        </div>
                        <div class="flex flex-col items-end ml-2">
                            <span
                                class="bg-cyan-100 text-cyan-600 text-sm font-semibold px-3 py-1 rounded-full">Completed</span>
                            <span class="text-gray-400 text-sm mt-2">1 hour ago</span>
                        </div>
                    </div>

                    <div
                        class="bg-white rounded-md shadow-sm border-l-4 border-yellow-500 h-[104px] p-4 flex items-center">
                        <div
                            class="w-10 h-10 rounded-full bg-yellow-100 text-yellow-600 flex items-center justify-center mr-3">
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24"
                                fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                stroke-linejoin="round" class="feather feather-alert-triangle">
                                <path
                                    d="M10.29 3.86L1.82 15a2 2 0 0 0 1.73 3h16.9a2 2 0 0 0 1.73-3l-8.47-11.14a2 2 0 0 0-3.46 0z">
                                </path>
                                <line x1="12" y1="9" x2="12" y2="13"></line>
                                <line x1="12" y1="17" x2="12" y2="17"></line>
                            </svg>
                        </div>
                        <div class="flex-1">
                            <h6 class="font-semibold text-gray-800 text-lg">
                                Overdue task: Client presentation prep
                            </h6>
                            <p class="text-gray-500 text-sm">
                                Your task for preparing the client presentation is now
                                overdue.
                            </p>
                        </div>
                        <div class="flex flex-col items-end ml-2">
                            <span
                                class="bg-yellow-100 text-yellow-600 text-sm font-semibold px-3 py-1 rounded-full">Overdue</span>
                            <span class="text-gray-400 text-sm mt-2">Yesterday</span>
                        </div>
                    </div>

                    <div
                        class="bg-white rounded-md shadow-sm border-l-4 border-indigo-500 h-[104px] p-4 flex items-center">
                        <div
                            class="w-10 h-10 rounded-full bg-indigo-100 text-indigo-600 flex items-center justify-center mr-3">
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24"
                                fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                stroke-linejoin="round" class="feather feather-mail">
                                <path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z">
                                </path>
                                <polyline points="22 6 12 13 2 6"></polyline>
                            </svg>
                        </div>
                        <div class="flex-1">
                            <h6 class="font-semibold text-gray-800 text-lg">
                                New message from Emma Wilson
                            </h6>
                            <p class="text-gray-500 text-sm">
                                Emma has sent you a message regarding the upcoming project
                                meeting.
                            </p>
                        </div>
                        <div class="flex flex-col items-end ml-2">
                            <span
                                class="bg-green-100 text-green-600 text-sm font-semibold px-3 py-1 rounded-full">New</span>
                            <span class="text-gray-400 text-sm mt-2">2 days ago</span>
                        </div>
                    </div>

                    <div
                        class="bg-white rounded-md shadow-sm border-l-4 border-yellow-500 h-[104px] p-4 flex items-center">
                        <div
                            class="w-10 h-10 rounded-full bg-yellow-100 text-yellow-600 flex items-center justify-center mr-3">
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24"
                                fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                stroke-linejoin="round" class="feather feather-alert-triangle">
                                <path
                                    d="M10.29 3.86L1.82 15a2 2 0 0 0 1.73 3h16.9a2 2 0 0 0 1.73-3l-8.47-11.14a2 2 0 0 0-3.46 0z">
                                </path>
                                <line x1="12" y1="9" x2="12" y2="13"></line>
                                <line x1="12" y1="17" x2="12" y2="17"></line>
                            </svg>
                        </div>
                        <div class="flex-1">
                            <h6 class="font-semibold text-gray-800 text-lg">
                                Overdue task: Client presentation prep
                            </h6>
                            <p class="text-gray-500 text-sm">
                                Your task for preparing the client presentation is now
                                overdue.
                            </p>
                        </div>
                        <div class="flex flex-col items-end ml-2">
                            <span
                                class="bg-yellow-100 text-yellow-600 text-sm font-semibold px-3 py-1 rounded-full">Overdue</span>
                            <span class="text-gray-400 text-sm mt-2">Yesterday</span>
                        </div>
                    </div>
                </div>
            </main>
        </div>
    </div>
</template>
