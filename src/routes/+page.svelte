<script>
  import { Navbar, NavBrand, NavHamburger, NavUl, NavLi, Button, DarkMode } from 'flowbite-svelte';
  import { MetaTag } from './utils';
  import {
    AdvancedTable,
    AccountRecoverysection,
    Bannersection,
    Blogsection,
    BlogTemplatesection,
    CommentSection,
    ContactFormsection,
    Contentsection,
    CookieConsentsection,
    CrudCreateDrawer,
    CrudCreateForm,
    CrudCreateModal,
    CrudDeleteConfirm,
    CrudReadDrawer,
    CrudReadModal,
    CrudReadSection,
    CrudSuccessMessage,
    CrudUpdateDrawer,
    CrudUpdateForm,
    CrudUpdateModal,
    Cta,
    DashboardFooter,
    DashboardNavbar,
    DropdownFilter,
    FacetedSearchDrawerSection,
    FacetedSearchModalSection,
    Faqsection,
    Featuresection,
    Footersection,
    Headersection,
    Herosection,
    LoginFormsection,
    Maintenancesection,
    Newslettersection,
    Page404section,
    Page500section,
    Popupsection,
    Portfoliosection,
    Pricingsection,
    ProjectPortfolioSection,
    RegisterFormsection,
    RelatedArticle,
    ResetPasswordFormsection,
    Schedulesection,
    SideNavigation,
    SocialProofsection,
    Teamsection,
    Testimonialsection,
    TableFooter,
    TableHeader,
    UserOnboarding
  } from './sections';

  let navClass = 'bg-white border-gray-200 px-4 py-2.5 dark:bg-gray-800';
  let navDivClass = 'flex flex-wrap justify-between items-center mx-auto max-w-8xl lg:px-4';
  let btnClass =
    'text-gray-500 dark:text-gray-400 hover:bg-gray-100 dark:hover:bg-gray-700 focus:outline-none focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-700 rounded-lg text-sm p-2 ml-2';
  const title = '';
  const breadcrumb_title = 'Flowbite Svelte Blocks';
  const description =
    'Get started with 250 free and premium UI components built with the utility classes from Tailwind CSS to upgrade your web development stack and customize the colors, fonts, and dark mode using the configurator.';
</script>

<MetaTag {breadcrumb_title} {title} {description} withoutLink={true} />

<div class="flex flex-col min-h-screen bg-white dark:bg-gray-900">
  <div class="px-4 mx-auto max-w-8xl dark:bg-gray-900">
    <main class="grow">
      <section class="mx-auto max-w-8xl">
        <div class="grid mt-3 mb-6 lg:gap-8 lg:mt-5 lg:mb-6 xl:grid-cols-3">
          <div class="col-span-2 mb-2 lg:mb-0">
            <h1 class="mb-2 text-3xl font-extrabold tracking-tight text-gray-900 dark:text-white">
              Flowbite Blocks in Svelte
            </h1>
            <p class="text-lg text-gray-500 xl:mr-64 lg:mb-0 dark:text-gray-400">
              Get started with 122 free and premium UI components built with the utility classes
              from Tailwind CSS to upgrade your web development stack and customize the colors,
              fonts, and dark mode using the configurator.
            </p>
          </div>
        </div>
      </section>
      <section class="pb-8 bg-white dark:bg-gray-900 lg:pb-24" id="components">
        <div class="mx-auto max-w-8xl lg:text-center">
          <div class="grid grid-cols-1 gap-6 mt-6 md:grid-cols-2 xl:grid-cols-3">
            <AccountRecoverysection />
            <AdvancedTable />
            <Bannersection />
            <Blogsection />
            <BlogTemplatesection />
            <CommentSection />
            <ContactFormsection />
            <Contentsection />
            <CookieConsentsection />
            <CrudCreateDrawer />
            <CrudCreateForm />
            <CrudCreateModal />
            <CrudDeleteConfirm />
            <CrudReadDrawer />
            <CrudReadModal />
            <CrudReadSection />
            <CrudSuccessMessage />
            <CrudUpdateDrawer />
            <CrudUpdateForm />
            <CrudUpdateModal />
            <Cta />
            <DashboardFooter />
            <DashboardNavbar />
            <DropdownFilter />
            <FacetedSearchDrawerSection />
            <FacetedSearchModalSection />
            <Faqsection />
            <Featuresection />
            <Footersection />
            <Headersection />
            <Herosection />
            <LoginFormsection />
            <Maintenancesection />
            <Newslettersection />
            <Page404section />
            <Page500section />
            <Popupsection />
            <Portfoliosection />
            <Pricingsection />
            <ProjectPortfolioSection />
            <RegisterFormsection />
            <RelatedArticle />
            <ResetPasswordFormsection />
            <Schedulesection />
            <SideNavigation />
            <SocialProofsection />
            <Teamsection />
            <Testimonialsection />
            <TableFooter />
            <TableHeader />
            <UserOnboarding />
          </div>
        </div>
      </section>
    </main>
  </div>
</div>
