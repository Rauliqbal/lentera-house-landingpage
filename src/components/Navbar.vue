<template>
    <nav
        class="relative w-full flex flex-wrap items-center justify-between py-5 text-gray-500 hover:text-gray-700 focus:text-gray-700  navbar navbar-expand-lg navbar-light"
    >
        <div
            class="container-fluid w-full flex flex-wrap items-center justify-between px-6"
        >
            <button
                class="navbar-toggler text-gray-500 border-0 hover:shadow-none hover:no-underline py-2 px-2.5 bg-transparent focus:outline-none focus:ring-0 focus:shadow-none focus:no-underline"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent"
                aria-expanded="false"
                aria-label="Toggle navigation"
            >
                <svg
                    aria-hidden="true"
                    focusable="false"
                    data-prefix="fas"
                    data-icon="bars"
                    class="w-6"
                    role="img"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 448 512"
                >
                    <path
                        fill="currentColor"
                        d="M16 132h416c8.837 0 16-7.163 16-16V76c0-8.837-7.163-16-16-16H16C7.163 60 0 67.163 0 76v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16z"
                    ></path>
                </svg>
            </button>
            <div
                class="collapse navbar-collapse flex-grow items-center"
                id="navbarSupportedContent"
            >
                <a class="text-xl text-black font-poppins" href="#">
                    <img class="w-14" src="../assets/images/logo.png" alt="">
                </a>
                <!-- Left links -->
                <ul
                    class="navbar-nav flex flex-col pl-0 list-style-none ml-auto gap-8"
                >
                    <li class="nav-item">
                        <a class="nav-link active font-semibold" aria-current="page" href="#"
                            >Home</a
                        >
                    </li>
                    <li class="nav-item">
                        <a
                            class="nav-link text-gray-500 hover:text-gray-700 focus:text-gray-700 p-0"
                            href="#"
                            >Location</a
                        >
                    </li>
                    <li class="nav-item">
                        <a
                            class="nav-link text-gray-500 hover:text-gray-700 focus:text-gray-700 p-0"
                            href="#"
                            >Success</a
                        >
                    </li>
                    <li class="nav-item">
                        <a class="nav-link  text-gray-500 hover:text-gray-700 focus:text-gray-700 p-0"
                            href="#">Features</a
                        >
                    </li>
                    <li class="nav-item">
                        <a class="nav-link  text-gray-500 hover:text-gray-700 focus:text-gray-700 p-0"
                            href="#">Account</a
                        >
                    </li>
                </ul>
                <!-- Left links -->
            </div>
            <!-- Collapsible wrapper -->
        </div>
    </nav>
</template>
