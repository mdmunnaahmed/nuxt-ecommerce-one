<template>
  <header class="w-full">
    <div class="header-area">
      <div class="main-header">
        <div class="top-menu-wrapper d-none d-lg-block">
          <div class="container">
            <div class="row">
              <div class="col-lg-12">
                <div class="d-flex align-items-center justify-content-between">
                  <!-- Top Left Side -->
                  <div class="top-header-left d-flex align-items-center">
                    <div class="top-menu">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                      >
                        <path
                          d="M2.02618 16.0002C1.92202 15.9752 1.81368 15.9543 1.70952 15.9293C0.651183 15.6585 -0.06965 14.6585 0.00535 13.5585C0.0761833 12.4877 0.909517 11.6044 1.98035 11.4627C3.10535 11.3127 4.16368 12.0169 4.46785 13.1127C4.48035 13.1544 4.49285 13.1918 4.50952 13.2502C4.55535 13.2502 4.60535 13.2502 4.65535 13.2502C6.03452 13.2502 7.40952 13.2502 8.78868 13.2502C8.89285 13.2502 8.94702 13.2252 8.99702 13.121C9.25952 12.5668 9.70535 12.2627 10.3179 12.2627C10.9262 12.2627 11.3762 12.5585 11.6429 13.1127C11.6929 13.2169 11.7429 13.2544 11.8595 13.2544C12.3262 13.246 12.797 13.2543 13.2637 13.2502C14.2845 13.2377 15.0804 12.396 15.0387 11.3752C15.0054 10.4877 14.272 9.71268 13.3845 9.68768C12.272 9.65852 11.1595 9.68352 10.047 9.66685C9.81785 9.66268 9.69285 9.71268 9.56785 9.93352C9.28452 10.4502 8.80952 10.696 8.21785 10.6544C7.65118 10.6168 7.24702 10.3168 7.00118 9.80852C6.95118 9.70018 6.89702 9.66685 6.78035 9.67102C5.98868 9.67518 5.20118 9.67518 4.40952 9.67102C3.44285 9.66685 2.65535 9.07102 2.43868 8.18768C2.12618 6.92102 3.06368 5.72935 4.38035 5.72935C6.79285 5.72518 9.20535 5.72935 11.6137 5.72935C11.6762 5.72935 11.7387 5.72935 11.8387 5.72935C11.7595 5.63352 11.7012 5.56268 11.647 5.49185C11.2637 5.01685 10.9262 4.51685 10.6304 3.97935C9.79702 2.44602 10.7387 0.733516 12.0637 0.221016C12.3179 0.121016 12.5887 0.0751831 12.8554 0.000183105C13.0512 0.000183105 13.2512 0.000183105 13.447 0.000183105C13.4762 0.00851644 13.5054 0.0251831 13.5345 0.0293498C14.6762 0.187683 15.6012 1.02102 15.8845 2.14185C15.9179 2.27102 15.9429 2.40018 15.972 2.53352C15.972 2.71268 15.972 2.88768 15.972 3.06685C15.7595 4.01268 15.2137 4.77518 14.622 5.51268C14.4387 5.74185 14.2345 5.94602 14.0554 6.17518C13.7678 6.54185 13.4054 6.67935 12.9429 6.67518C10.122 6.66268 7.30118 6.67102 4.47618 6.67102C4.39285 6.67102 4.30952 6.67102 4.22618 6.68352C3.59702 6.75852 3.19285 7.34602 3.34285 7.96268C3.45952 8.43352 3.87202 8.73768 4.41368 8.74185C5.19702 8.74602 5.98452 8.74185 6.76785 8.74602C6.88452 8.74602 6.94285 8.71685 7.00118 8.60018C7.26785 8.05852 7.70535 7.75852 8.31368 7.75435C8.92202 7.75018 9.36368 8.04602 9.63452 8.58768C9.69702 8.71268 9.75952 8.74602 9.88868 8.74602C11.0012 8.74185 12.1137 8.73768 13.2262 8.74602C14.522 8.75018 15.597 9.59185 15.9012 10.8335C15.9304 10.9544 15.9512 11.0752 15.9762 11.196C15.9762 11.3835 15.9762 11.571 15.9762 11.7585C15.9679 11.7752 15.9554 11.796 15.9512 11.8127C15.8137 13.0627 14.7012 14.2335 13.147 14.196C12.722 14.1877 12.2929 14.2002 11.8679 14.1919C11.747 14.1877 11.6887 14.2252 11.6345 14.3377C11.3679 14.8919 10.9179 15.1877 10.3095 15.1835C9.70535 15.1793 9.26368 14.8794 8.99702 14.3335C8.94702 14.2294 8.90118 14.1919 8.78035 14.1919C7.40952 14.196 6.03868 14.196 4.66368 14.196C4.61368 14.196 4.55952 14.196 4.50952 14.196C4.49285 14.2502 4.47618 14.296 4.46368 14.3377C4.22202 15.1252 3.70535 15.6502 2.91368 15.9044C2.78452 15.946 2.65535 15.9669 2.52202 16.0002C2.35952 16.0002 2.19285 16.0002 2.02618 16.0002ZM13.1387 0.937683C11.8262 0.91685 10.747 2.38768 11.4887 3.62518C11.9304 4.36268 12.4512 5.02935 13.0262 5.66268C13.1054 5.75018 13.1762 5.74185 13.247 5.65852C13.372 5.51685 13.5012 5.38352 13.622 5.23768C14.1054 4.66685 14.572 4.07935 14.8845 3.39185C14.9887 3.16685 15.0512 2.93352 15.0262 2.68352C14.9429 1.70018 14.1179 0.937683 13.1387 0.937683ZM2.26785 15.0627C3.00535 15.0669 3.61368 14.4627 3.61368 13.7252C3.61785 12.9877 3.01368 12.3793 2.28035 12.3752C1.54285 12.371 0.938683 12.9752 0.934517 13.7127C0.93035 14.4544 1.53035 15.0585 2.26785 15.0627ZM10.8345 13.7127C10.8304 13.421 10.5887 13.1877 10.3054 13.196C10.022 13.2044 9.79285 13.4377 9.79285 13.7169C9.79285 14.0044 10.0304 14.246 10.3179 14.2418C10.6054 14.2418 10.8387 14.0044 10.8345 13.7127ZM8.83035 9.20018C8.83035 8.90852 8.59702 8.68352 8.30535 8.68352C8.01368 8.68768 7.78868 8.92102 7.79285 9.21268C7.79702 9.49602 8.02618 9.72102 8.31368 9.72102C8.60535 9.72518 8.83452 9.49185 8.83035 9.20018Z"
                          fill="#AD8C5C"
                        />
                        <path
                          d="M13.1345 2.40005C13.3929 2.40005 13.597 2.61672 13.597 2.88339C13.597 3.12089 13.3762 3.33339 13.1304 3.33339C12.8804 3.33339 12.6637 3.10422 12.6637 2.84589C12.6679 2.61256 12.8887 2.40005 13.1345 2.40005Z"
                          fill="#AD8C5C"
                        />
                      </svg>
                      <nuxt-link href="">
                        <p class="pera text-color-primary">Track Your Order</p>
                      </nuxt-link>
                    </div>
                    <div class="top-menu">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="18"
                        height="13"
                        viewBox="0 0 18 13"
                        fill="none"
                      >
                        <path
                          d="M17.2021 1.33173C17.2021 4.77563 17.2021 8.21953 17.2021 11.6634C17.198 11.6718 17.1897 11.6843 17.1897 11.6926C17.0691 12.4941 16.3995 13.0243 15.5511 12.9992C14.8108 12.9784 14.0664 12.9951 13.3261 12.9951C9.47914 12.9951 5.63219 12.9951 1.78525 12.9951C0.86198 12.9951 0.20488 12.3606 0.20488 11.4547C0.200721 8.15274 0.200721 4.8466 0.209039 1.54045C0.209039 1.31086 0.267263 1.06039 0.362917 0.851674C0.64572 0.258906 1.1531 9.15527e-05 1.80188 9.15527e-05C6.40158 9.15527e-05 11.0013 9.15527e-05 15.5968 9.15527e-05C15.6343 9.15527e-05 15.6758 9.15527e-05 15.7133 9.15527e-05C16.1874 0.0209637 16.5783 0.204638 16.8778 0.576162C17.0607 0.801581 17.1398 1.06457 17.2021 1.33173ZM1.91417 1.0103C4.20155 3.28536 6.45981 5.53537 8.70559 7.76452C10.9597 5.50198 13.2013 3.25197 15.4388 1.0103C10.9555 1.0103 6.45565 1.0103 1.91417 1.0103ZM15.443 11.989C13.8709 10.4111 12.2905 8.82482 10.706 7.23436C10.6769 7.26359 10.6311 7.30533 10.5896 7.34707C10.1154 7.82296 9.64134 8.29884 9.16723 8.77055C8.86363 9.07528 8.60994 9.07528 8.29803 8.76638C7.81144 8.28214 7.32485 7.79791 6.83826 7.3095C6.79668 7.26776 6.77588 7.20097 6.75925 7.17592C5.12897 8.8123 3.54445 10.4028 1.96408 11.989C6.44733 11.989 10.9514 11.989 15.443 11.989ZM1.21132 1.71578C1.21132 4.92173 1.21132 8.08595 1.21132 11.2543C2.80417 9.65553 4.3887 8.06925 5.98154 6.46627C4.40117 4.89251 2.81665 3.31458 1.21132 1.71578ZM11.4837 6.49967C13.0474 8.06925 14.6237 9.65135 16.1957 11.2293C16.1957 8.08177 16.1957 4.91339 16.1957 1.77005C14.6278 3.34798 13.0474 4.93008 11.4837 6.49967Z"
                          fill="#AD8C5C"
                        />
                      </svg>
                      <nuxt-link href="javascript:void(0)">
                        <p class="pera text-color-secondary">
                          infoyour@gmail.com
                        </p>
                      </nuxt-link>
                    </div>
                  </div>
                  <!--Top Right Side -->
                  <div class="top-header-right">
                    <!-- country dropdwon -->
                    <div class="dropdown-side-divider">
                      <select class="country-select" name="country"></select>
                    </div>
                    <!-- Currency dropdown -->
                    <div class="dropdown-side-divider ml-40">
                      <select class="select2" name="currency">
                        <option value="usd">USD</option>
                        <option value="bdt">BDT</option>
                        <option value="cad">CAD</option>
                      </select>
                    </div>
                    <!-- login/register -->
                    <div class="login-wrapper ml-48">
                      <svg
                        width="20"
                        height="20"
                        viewBox="0 0 26 26"
                        fill="none"
                        xmlns="http://www.w3.org/2000/svg"
                      >
                        <g clip-path="url(#clip0_366_11241)">
                          <path
                            fill-rule="evenodd"
                            clip-rule="evenodd"
                            d="M13 1.75C6.7868 1.75 1.75 6.7868 1.75 13C1.75 16.0203 2.9395 18.7622 4.8774 20.7837C6.40175 17.853 9.4662 15.85 13 15.85C16.5338 15.85 19.5983 17.853 21.1226 20.7837C23.0605 18.7622 24.25 16.0203 24.25 13C24.25 6.7868 19.2132 1.75 13 1.75ZM19.9665 21.8341C18.762 19.188 16.0948 17.35 13 17.35C9.9052 17.35 7.23801 19.188 6.03354 21.8341C7.94968 23.3474 10.3686 24.25 13 24.25C15.6314 24.25 18.0503 23.3474 19.9665 21.8341ZM0.25 13C0.25 5.95837 5.95837 0.25 13 0.25C20.0416 0.25 25.75 5.95837 25.75 13C25.75 16.8422 24.0496 20.2881 21.3627 22.6245C19.1245 24.5709 16.199 25.75 13 25.75C9.80096 25.75 6.87546 24.5709 4.63726 22.6245C1.95044 20.2881 0.25 16.8422 0.25 13Z"
                            fill="black"
                          ></path>
                          <path
                            fill-rule="evenodd"
                            clip-rule="evenodd"
                            d="M13 12.25C11.6193 12.25 10.5 11.1307 10.5 9.75C10.5 8.36929 11.6193 7.25 13 7.25C14.3807 7.25 15.5 8.36929 15.5 9.75C15.5 11.1307 14.3807 12.25 13 12.25ZM9 9.75C9 11.9591 10.7909 13.75 13 13.75C15.2091 13.75 17 11.9591 17 9.75C17 7.54086 15.2091 5.75 13 5.75C10.7909 5.75 9 7.54086 9 9.75Z"
                            fill="black"
                          ></path>
                        </g>
                        <defs>
                          <clipPath id="clip0_366_11241">
                            <rect width="26" height="26" fill="white"></rect>
                          </clipPath>
                        </defs>
                      </svg>
                      <nuxt-link href="/login">
                        <p class="pera text-color-primary">Login / Regeister</p>
                      </nuxt-link>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="header-bottom header-sticky">
          <div class="container">
            <div class="row">
              <div class="col-lg-12">
                <div class="menu-wrapper">
                  <!-- Main-menu for desktop -->
                  <div class="main-menu">
                    <nav>
                      <div
                        class="d-flex justify-content-between align-items-center"
                      >
                        <!-- Logo-->
                        <div class="logo logo-large light-logo">
                          <nuxt-link href="/"
                            ><img src="/images/logo/logo.png" alt="logo"
                          /></nuxt-link>
                        </div>
                        <div class="search-header-position d-block d-lg-none">
                          <div class="d-flex gap-15">
                            <div class="search-bar">
                              <nuxt-link
                                href="javascript:void(0)"
                                class="rounded-btn"
                              >
                                <i class="ri-search-line"></i>
                              </nuxt-link>
                            </div>
                          </div>
                        </div>
                        <ul class="listing d-none d-lg-block" id="navigation">
                          <li class="single-list">
                            <nuxt-link href="javascript:void(0)" class="single"
                              >Home <i class="ri-arrow-down-s-line"></i
                            ></nuxt-link>
                            <ul class="submenu">
                              <li class="single-list">
                                <nuxt-link href="/" class="single"
                                  >Home 01</nuxt-link
                                >
                              </li>
                              <li class="single-list">
                                <nuxt-link href="/home-two" class="single"
                                  >Home 02</nuxt-link
                                >
                              </li>
                            </ul>
                          </li>
                          <li class="single-list">
                            <nuxt-link href="/about" class="single"
                              >About</nuxt-link
                            >
                          </li>
                          <li class="single-list">
                            <nuxt-link href="/shop" class="single"
                              >Shop</nuxt-link
                            >
                          </li>
                          <li class="single-list">
                            <nuxt-link href="/blog" class="single"
                              >Blog</nuxt-link
                            >
                          </li>
                          <li class="single-list">
                            <nuxt-link href="javascript:void(0)" class="single"
                              >Pages <i class="ri-arrow-down-s-line"></i
                            ></nuxt-link>
                            <ul class="submenu">
                              <li class="single-list">
                                <nuxt-link href="wishlist.html" class="single"
                                  >Wishlist</nuxt-link
                                >
                              </li>
                              <li class="single-list">
                                <nuxt-link
                                  href="javascript:void(0)"
                                  class="single"
                                  >Login<i class="ri-arrow-right-s-line"></i
                                ></nuxt-link>
                                <ul class="submenu">
                                  <li class="single-list">
                                    <nuxt-link href="/login" class="single"
                                      >Login</nuxt-link
                                    >
                                  </li>
                                  <li class="single-list">
                                    <nuxt-link
                                      href="register.html"
                                      class="single"
                                      >Registration</nuxt-link
                                    >
                                  </li>
                                  <li class="single-list">
                                    <nuxt-link
                                      href="forgot-pass.html"
                                      class="single"
                                      >Forgot Password</nuxt-link
                                    >
                                  </li>
                                  <li class="single-list">
                                    <nuxt-link
                                      href="verification.html"
                                      class="single"
                                      >Verification</nuxt-link
                                    >
                                  </li>
                                  <li class="single-list">
                                    <nuxt-link
                                      href="new-password.html"
                                      class="single"
                                      >New Password</nuxt-link
                                    >
                                  </li>
                                </ul>
                              </li>

                              <li class="single-list">
                                <nuxt-link href="/faq" class="single"
                                  >FAQs</nuxt-link
                                >
                              </li>
                              <li class="single-list">
                                <nuxt-link href="/privacy-policy" class="single"
                                  >privacy policy</nuxt-link
                                >
                              </li>
                              <li class="single-list">
                                <nuxt-link
                                  href="/terms-condition"
                                  class="single"
                                  >terms-condition</nuxt-link
                                >
                              </li>
                            </ul>
                          </li>
                          <li class="single-list">
                            <nuxt-link href="/contact" class="single"
                              >Contact</nuxt-link
                            >
                          </li>
                          <li class="d-block d-lg-none">
                            <div class="login-wrapper">
                              <nuxt-link href="/login">
                                <p class="pera text-color-primary">
                                  Login/ Regeister
                                </p>
                              </nuxt-link>
                            </div>
                          </li>
                          <li class="d-block d-lg-none">
                            <div class="login-wrapper">
                              <nuxt-link href="/shopping-cart">
                                <p class="pera text-color-primary">Cart</p>
                              </nuxt-link>
                            </div>
                          </li>
                          <li class="d-block d-lg-none">
                            <div class="login-wrapper">
                              <nuxt-link href="/wishlist">
                                <p class="pera text-color-primary">Wishlist</p>
                              </nuxt-link>
                            </div>
                          </li>
                          <li class="d-block d-lg-none">
                            <div class="login-wrapper">
                              <nuxt-link href="/order-track">
                                <p class="pera text-color-primary">
                                  Track Order
                                </p>
                              </nuxt-link>
                            </div>
                          </li>
                        </ul>
                        <div class="d-none d-lg-block">
                          <div class="header-right">
                            <div class="header-icon" v-if="isLoggedIn">
                              <nuxt-link href="/profile">
                                <svg
                                  width="26"
                                  height="26"
                                  viewBox="0 0 26 26"
                                  fill="none"
                                  xmlns="http://www.w3.org/2000/svg"
                                >
                                  <g clip-path="url(#clip0_366_11241)">
                                    <path
                                      fill-rule="evenodd"
                                      clip-rule="evenodd"
                                      d="M13 1.75C6.7868 1.75 1.75 6.7868 1.75 13C1.75 16.0203 2.9395 18.7622 4.8774 20.7837C6.40175 17.853 9.4662 15.85 13 15.85C16.5338 15.85 19.5983 17.853 21.1226 20.7837C23.0605 18.7622 24.25 16.0203 24.25 13C24.25 6.7868 19.2132 1.75 13 1.75ZM19.9665 21.8341C18.762 19.188 16.0948 17.35 13 17.35C9.9052 17.35 7.23801 19.188 6.03354 21.8341C7.94968 23.3474 10.3686 24.25 13 24.25C15.6314 24.25 18.0503 23.3474 19.9665 21.8341ZM0.25 13C0.25 5.95837 5.95837 0.25 13 0.25C20.0416 0.25 25.75 5.95837 25.75 13C25.75 16.8422 24.0496 20.2881 21.3627 22.6245C19.1245 24.5709 16.199 25.75 13 25.75C9.80096 25.75 6.87546 24.5709 4.63726 22.6245C1.95044 20.2881 0.25 16.8422 0.25 13Z"
                                      fill="currentColor"
                                    />
                                    <path
                                      fill-rule="evenodd"
                                      clip-rule="evenodd"
                                      d="M13 12.25C11.6193 12.25 10.5 11.1307 10.5 9.75C10.5 8.36929 11.6193 7.25 13 7.25C14.3807 7.25 15.5 8.36929 15.5 9.75C15.5 11.1307 14.3807 12.25 13 12.25ZM9 9.75C9 11.9591 10.7909 13.75 13 13.75C15.2091 13.75 17 11.9591 17 9.75C17 7.54086 15.2091 5.75 13 5.75C10.7909 5.75 9 7.54086 9 9.75Z"
                                      fill="currentColor"
                                    />
                                  </g>
                                  <defs>
                                    <clipPath id="clip0_366_11241">
                                      <rect
                                        width="26"
                                        height="26"
                                        fill="white"
                                      />
                                    </clipPath>
                                  </defs>
                                </svg>
                              </nuxt-link>
                            </div>
                            <div class="header-icon">
                              <nuxt-link href="/cart">
                                <svg
                                  width="22"
                                  height="24"
                                  viewBox="0 0 22 24"
                                  fill="none"
                                  xmlns="http://www.w3.org/2000/svg"
                                >
                                  <path
                                    d="M19.7472 6.21264C19.5903 5.81551 19.2308 5.78119 17.464 5.78119H15.9959V5.15364C15.9959 4.17798 15.8541 3.49649 15.5099 2.79539C14.8872 1.52556 13.8443 0.638157 12.4926 0.226322C11.8345 0.0302096 10.8524 -0.053138 10.255 0.0351124C8.59958 0.290058 7.18715 1.31474 6.46828 2.77578C6.11896 3.49159 5.97721 4.17798 5.97721 5.15364V5.7861H4.50403C2.73722 5.7861 2.37778 5.82042 2.22084 6.23225C2.13984 6.4921 1.38047 12.0764 1.05647 14.4837C0.772972 16.5821 0.509722 18.5628 0.317347 20.0532C-0.0167771 22.6223 -0.00665214 22.6615 0.00347284 22.7057V22.7106C0.0490353 22.8773 0.499597 23.3136 0.636284 23.4411L1.2286 24H20.7091L21.1495 23.6225C21.3469 23.4509 22 22.8675 22 22.5782C22 22.3821 19.7877 6.32541 19.7472 6.21264ZM20.4003 22.2056C20.3952 22.2399 20.3547 22.3429 20.2838 22.4164L20.1826 22.5243H1.79053L1.52728 22.2497L2.56509 14.7435C2.92959 12.0715 3.25359 9.74266 3.44597 8.35026C3.53203 7.74231 3.57253 7.43344 3.59278 7.28145C4.27622 7.27655 7.26309 7.27165 10.979 7.27165H18.3702L18.3803 7.32558C18.4613 7.7178 20.3648 21.7692 20.4003 22.2056ZM7.50102 5.7861V5.22718C7.50102 4.84966 7.55165 4.32997 7.60734 4.08973C7.90602 2.86403 8.92358 1.86876 10.1943 1.55008C10.7258 1.4226 11.5966 1.46673 12.1281 1.65304H12.1332C12.6901 1.83444 13.1457 2.12861 13.5659 2.57967C14.2443 3.29547 14.4721 3.93774 14.4721 5.12422V5.7861H7.50102Z"
                                    fill="#13172B"
                                  />
                                </svg>

                                <div class="count">
                                  <span class="count-num">{{ userItems }}</span>
                                </div>
                              </nuxt-link>
                            </div>
                          </div>
                        </div>
                      </div>
                    </nav>
                  </div>
                  <!-- Mobile Menu -->
                  <div class="div">
                    <div class="mobile_menu d-block d-lg-none"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script setup>
import { useAuthStore } from "~/stores/authStore";
import { useFrontStore } from "~/stores/frontStore";
const authStore = useAuthStore();

const frontStore = useFrontStore();
const isLoggedIn = computed(() => {
  return authStore.isLoggedIn;
});
const user = computed(() => {
  return authStore.authUser ? authStore.authUser.username : "";
});


const userItems = (() => {
  return frontStore.getItemsByUsername(user).length;
});
</script>
