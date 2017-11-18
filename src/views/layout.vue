<template>
    <div id="app">
<header id="header_main">
        <div class="header_main_content">
            <nav class="uk-navbar">
              	<div class="main_logo_top">
                        <a href="index.html"><img src="assets/img/logo_main_white.png" alt="" width="71" height="15"></a>
                    </div>
                                
                <!-- main sidebar switch -->
                <a href="#" id="sidebar_main_toggle" class="sSwitch sSwitch_left">
                    <span class="sSwitchIcon"></span>
                </a>
                
                <!-- secondary sidebar switch -->
                <a href="#" id="sidebar_secondary_toggle" class="sSwitch sSwitch_right sidebar_secondary_check">
                    <span class="sSwitchIcon"></span>
                </a>
                
                    <div id="menu_top_dropdown" class="uk-float-left uk-hidden-small">
\					</div>
                
                <div class="uk-navbar-flip">
                    <ul class="uk-navbar-nav user_actions">
                        <li><a href="#" id="full_screen_toggle" class="user_action_icon uk-visible-large"><i class="material-icons md-24 md-light"></i></a></li>
                        <li><a href="#" id="main_search_btn" class="user_action_icon"><i class="material-icons md-24 md-light"></i></a></li>
                        <li data-uk-dropdown="{mode:'click',pos:'bottom-right'}">
                            <a href="#" class="user_action_icon"><i class="material-icons md-24 md-light"></i><span class="uk-badge">16</span></a>
                            <div class="uk-dropdown uk-dropdown-xlarge">
                                <div class="md-card-content">
                                    <ul class="uk-tab uk-tab-grid" data-uk-tab="{connect:'#header_alerts',animation:'slide-horizontal'}">
                                        <li class="uk-width-1-2 uk-active" aria-expanded="true"><a href="#" class="js-uk-prevent uk-text-small">Messages (12)</a></li>
                                        <li class="uk-width-1-2" aria-expanded="false"><a href="#" class="js-uk-prevent uk-text-small">Alerts (4)</a></li>
                                    <li class="uk-tab-responsive uk-active uk-hidden" aria-haspopup="true" aria-expanded="false"><a>Messages (12)</a><div class="uk-dropdown uk-dropdown-small" aria-hidden="true"><ul class="uk-nav uk-nav-dropdown"></ul><div></div></div></li></ul>
                                    <ul id="header_alerts" class="uk-switcher uk-margin">
                                        <li aria-hidden="false" class="uk-active">
                                            <ul class="md-list md-list-addon">
                                                <li>
                                                    <div class="md-list-addon-element">
                                                        <span class="md-user-letters md-bg-cyan">mk</span>
                                                    </div>
                                                    <div class="md-list-content">
                                                        <span class="md-list-heading"><a href="page_mailbox.html">Quis adipisci officia.</a></span>
                                                        <span class="uk-text-small uk-text-muted">Debitis et id qui voluptatem adipisci officiis.</span>
                                                    </div>
                                                </li>
                                                <li>
                                                    <div class="md-list-addon-element">
                                                        <img class="md-user-image md-list-addon-avatar" src="assets/img/avatars/avatar_07_tn.png" alt="">
                                                    </div>
                                                    <div class="md-list-content">
                                                        <span class="md-list-heading"><a href="page_mailbox.html">Corporis qui eos.</a></span>
                                                        <span class="uk-text-small uk-text-muted">Facilis nisi distinctio iste voluptatem quia voluptatem animi.</span>
                                                    </div>
                                                </li>
                                                <li>
                                                    <div class="md-list-addon-element">
                                                        <span class="md-user-letters md-bg-light-green">vh</span>
                                                    </div>
                                                    <div class="md-list-content">
                                                        <span class="md-list-heading"><a href="page_mailbox.html">Dignissimos non.</a></span>
                                                        <span class="uk-text-small uk-text-muted">Ex velit tempora atque quidem reiciendis quos omnis.</span>
                                                    </div>
                                                </li>
                                                <li>
                                                    <div class="md-list-addon-element">
                                                        <img class="md-user-image md-list-addon-avatar" src="assets/img/avatars/avatar_02_tn.png" alt="">
                                                    </div>
                                                    <div class="md-list-content">
                                                        <span class="md-list-heading"><a href="page_mailbox.html">Sit aut nobis.</a></span>
                                                        <span class="uk-text-small uk-text-muted">Est dolorem quisquam harum et occaecati.</span>
                                                    </div>
                                                </li>
                                                <li>
                                                    <div class="md-list-addon-element">
                                                        <img class="md-user-image md-list-addon-avatar" src="assets/img/avatars/avatar_09_tn.png" alt="">
                                                    </div>
                                                    <div class="md-list-content">
                                                        <span class="md-list-heading"><a href="page_mailbox.html">Eligendi minus.</a></span>
                                                        <span class="uk-text-small uk-text-muted">Quibusdam ipsa voluptatum perferendis aut impedit et sint incidunt.</span>
                                                    </div>
                                                </li>
                                            </ul>
                                            <div class="uk-text-center uk-margin-top uk-margin-small-bottom">
                                                <a href="page_mailbox.html" class="md-btn md-btn-flat md-btn-flat-primary js-uk-prevent">Show All</a>
                                            </div>
                                        </li>
                                        <li aria-hidden="true">
                                            <ul class="md-list md-list-addon">
                                                <li>
                                                    <div class="md-list-addon-element">
                                                        <i class="md-list-addon-icon material-icons uk-text-warning"></i>
                                                    </div>
                                                    <div class="md-list-content">
                                                        <span class="md-list-heading">Minima est illum.</span>
                                                        <span class="uk-text-small uk-text-muted uk-text-truncate">Rem porro consequuntur qui laboriosam voluptatem provident vitae.</span>
                                                    </div>
                                                </li>
                                                <li>
                                                    <div class="md-list-addon-element">
                                                        <i class="md-list-addon-icon material-icons uk-text-success"></i>
                                                    </div>
                                                    <div class="md-list-content">
                                                        <span class="md-list-heading">Pariatur reprehenderit et.</span>
                                                        <span class="uk-text-small uk-text-muted uk-text-truncate">Sequi possimus tenetur aut vel consequuntur modi.</span>
                                                    </div>
                                                </li>
                                                <li>
                                                    <div class="md-list-addon-element">
                                                        <i class="md-list-addon-icon material-icons uk-text-danger"></i>
                                                    </div>
                                                    <div class="md-list-content">
                                                        <span class="md-list-heading">Totam expedita.</span>
                                                        <span class="uk-text-small uk-text-muted uk-text-truncate">Rerum aliquam et voluptatem.</span>
                                                    </div>
                                                </li>
                                                <li>
                                                    <div class="md-list-addon-element">
                                                        <i class="md-list-addon-icon material-icons uk-text-primary"></i>
                                                    </div>
                                                    <div class="md-list-content">
                                                        <span class="md-list-heading">Quia saepe earum.</span>
                                                        <span class="uk-text-small uk-text-muted uk-text-truncate">Provident sit non mollitia non ducimus.</span>
                                                    </div>
                                                </li>
                                            </ul>
                                        </li>
                                    </ul>
                                </div>
                            </div>
                        </li>
                        <li data-uk-dropdown="{mode:'click',pos:'bottom-right'}">
                            <a href="#" class="user_action_image"><img class="md-user-image" src="assets/img/avatars/avatar_11_tn.png" alt=""></a>
                            <div class="uk-dropdown uk-dropdown-small">
                                <ul class="uk-nav js-uk-prevent">
                                    <li><a href="page_user_profile.html">My profile</a></li>
                                    <li><a href="page_settings.html">Settings</a></li>
                                    <li><a href="login.html">Logout</a></li>
                                </ul>
                            </div>
                        </li>
                    </ul>
                </div>
            </nav>
        </div>
        <div class="header_main_search_form">
            <i class="md-icon header_main_search_close material-icons"></i>
            <form class="uk-form uk-autocomplete" data-uk-autocomplete="{source:'data/search_data.json'}">
                <input class="header_main_search_input" type="text">
                <button class="header_main_search_btn uk-button-link"><i class="md-icon material-icons"></i></button>
                <script async="" src="//www.google-analytics.com/analytics.js"></script><script src="http://ajax.googleapis.com/ajax/libs/webfont/1/webfont.js" type="text/javascript" async=""></script><script type="text/autocomplete">
                    <ul class="uk-nav uk-nav-autocomplete uk-autocomplete-results">
                        {{~items}}
                        <li data-value="{{ $item.value }}">
                            <a href="{{ $item.url }}" class="needsclick">
                                {{ $item.value }}<br>
                                <span class="uk-text-muted uk-text-small">{{{ $item.text }}}</span>
                            </a>
                        </li>
                        {{/items}}
                    </ul>
                </script>
            </form>
        </div>
    </header>

    </div>
</template>