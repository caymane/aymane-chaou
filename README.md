# aymane-chaoui 
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>MassarService</title>
    <!-- Tell the browser to be responsive to screen width -->
    <meta content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no" name="viewport">

    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">
    <!-- Ionicons -->
    <link rel="stylesheet" href="https://code.ionicframework.com/ionicons/2.0.1/css/ionicons.min.css">

    <script>
        var lang = 'ar';
        var culture = 'ar-MA';
    </script>


    <link href="/moutamadris/Content/bootstrap/css/bootstrap.min.css" rel="stylesheet"/>
<link href="/moutamadris/Content/bootstrap-rtl/css/bootstrap-rtl.min.css" rel="stylesheet"/>
<link href="/moutamadris/Content/dist/css/AdminLTE.min.css" rel="stylesheet"/>
<link href="/moutamadris/Content/dist/css/skins/_all-skins.min.css" rel="stylesheet"/>
<link href="/moutamadris/Content/dist/css/AdminLTE-rtl.min.css" rel="stylesheet"/>
<link href="/moutamadris/Content/dist/css/skins/_all-skins-rtl.min.css" rel="stylesheet"/>
<link href="/moutamadris/Content/plugins/datepicker/bootstrap-datepicker3.min.css" rel="stylesheet"/>
<link href="/moutamadris/Content/plugins/notifications/pnotify.custom.min.css" rel="stylesheet"/>
<link href="/moutamadris/Content/dropzone.css" rel="stylesheet"/>
<link href="/moutamadris/Content/bootstrap-dropdown-checkbox.css" rel="stylesheet"/>
<link href="/moutamadris/Content/plugins/select2/select2.min.css" rel="stylesheet"/>

    <link href="/moutamadris/Content/MassarService.style.css" rel="stylesheet"/>

    <script src="/moutamadris/Scripts/jquery-2.2.1.min.js"></script>
<script src="/moutamadris/Scripts/jquery.unobtrusive-ajax.min.js"></script>
<script src="/moutamadris/Scripts/jquery.validate.min.js"></script>
<script src="/moutamadris/Scripts/jquery.validate.unobtrusive.min.js"></script>
<script src="/moutamadris/Scripts/jquery.confirm.js"></script>
<script src="/moutamadris/Content/plugins/slimScroll/jquery.slimscroll.min.js"></script>
<script src="/moutamadris/Scripts/dropDownListFilteringHelper.js"></script>
<script src="/moutamadris/Scripts/requiredif.js"></script>
<script src="/moutamadris/Scripts/dropzone.js"></script>
<script src="/moutamadris/Content/plugins/datatables/jquery.dataTables.min.js"></script>
<script src="/moutamadris/Content/plugins/datatables/dataTables.bootstrap.min.js"></script>
<script src="/moutamadris/Scripts/bootstrap-dropdown-checkbox.min.js"></script>
<script src="/moutamadris/Scripts/jquery.globalize/globalize.js"></script>

    <script src="/moutamadris/Content/bootstrap/js/bootstrap.min.js"></script>
<script src="/moutamadris/Content/bootstrap/js/respond.min.js"></script>

    <script src="/moutamadris/Content/plugins/timepicker/bootstrap-timepicker.js"></script>
<script src="/moutamadris/Content/plugins/datepicker/bootstrap-datepicker.js"></script>
<script src="/moutamadris/Content/plugins/datepicker/bootstrap-datepicker.ar.min.js"></script>
<script src="/moutamadris/Content/plugins/datepicker/bootstrap-datepicker.fr.min.js"></script>
<script src="/moutamadris/Content/plugins/bootstrap-wysihtml5/bootstrap3-wysihtml5.all.min.js"></script>
<script src="/moutamadris/Content/dist/js/app.min.js"></script>
<script src="/moutamadris/Content/dist/js/demo.js"></script>
<script src="/moutamadris/Content/plugins/notifications/notifications-1.0.0.js"></script>
<script src="/moutamadris/Content/plugins/notifications/pnotify.custom.min.js"></script>
<script src="/moutamadris/Content/plugins/Popup/popup-manager.js"></script>
<script src="/moutamadris/Scripts/MassarService_Script.js"></script>
<script src="/moutamadris/Scripts/MassarService-input-Note.js"></script>
<script src="/moutamadris/Scripts/MassarService-input-IntegerOnly.js"></script>
<script src="/moutamadris/Scripts/MassarService-grid-navigation.js"></script>
<script src="/moutamadris/Content/plugins/select2/select2.full.js"></script>


    <script src="https://openam.github.io/bootstrap-responsive-tabs/js/responsive-tabs.js"></script>

    



</head>
<body class="hold-transition skin-blue sidebar-mini Layout Ar ">
    <div class="wrapper">
        <header class="main-header headerLayout">
            <!-- Logo -->
            <!-- Header Navbar: style can be found in header.less -->
            <img class="header-log" id="logo-men" src="/moutamadris/images/LogoMenAr.png" style="width: 350px;position:absolute;top: 34px;right: 86px;">
            <img class="header-log" id="logo-sgs" src="/moutamadris/images/logo_SGS.png" style="width: 180px;position:absolute;top: 13px;left: 40px;">
            <nav class="navbar navbar-static-top main-navbar" role="navigation">
                 <!-- Sidebar toggle but ton-->



<ul class="main-menu">
    <li class="first active"><a href="/moutamadris/General/Home" title="">&nbsp;</a></li>

    <li>
        <a href="https://moutamadris.men.gov.ma">المسار الدراسي</a>
    </li>

    <li>
        <a href="https://moutamadris.men.gov.ma">الدعم التربوي</a>
    </li>

    <li>
        <a href="https://moutamadris.men.gov.ma">التقويم والامتحانات</a>
    </li>

    <li>
        <a href="https://moutamadris.men.gov.ma">توجيه وتميز</a>
    </li>

        <li class="last">
            <a href="/moutamadris/General/SetCulture?culture=fr&amp;Url=%2Fmoutamadris%2FAccount">
                français
            </a>
        </li>

</ul>
            </nav>
        </header>

        <div class="content-wrapper">
            <!-- Content Header(Page header) -->

            <section class="content-header">
                <h1>  </h1>
            </section>

            <!-- Main content -->
            <section class="content" style="position: relative;">

                <div class="modals" id="loadingDiv"></div>

                <div class="row">
                    <div class="row col-md-12 col-sm-12 col-xs-12">
                        







<style>
    .Layout.Ar .form-control {
        direction: ltr;
    }
    .form-horizontal .has-feedback .form-control-feedback {
        left: 5px;
    }
    .content {
        padding: 0px !important;
    }

    .has-feedback .form-control {
        padding-left: 37px;
    }
</style>

    <table class="newHomeSli">
        <tbody>
            <tr>
                <td class="NewSilder">

                    <div class="newESP"></div>
                    <div class="Contact">
<form action="/moutamadris/Account" class="form-horizontal" method="post" role="form"><input name="__RequestVerificationToken" type="hidden" value="0u8ggw2rhfe46SZHN70oMSMBQ2mnHoQ9mgjhEsacZF5qeMZIqKjE8AoeAdhl5yjmRfYElqbeCFwnuUt-dkKN17gCQ001" /><div class="validation-summary-valid" data-valmsg-summary="true"><ul><li style="display:none"></li>
</ul></div>                            <div>
                                <table class="newEspTable">
                                    <tbody>
                                        <tr>
                                            <td colspan="2">
                                                <span class="validatorsLogin" style="color:Red;display:none;">البريد الإلكتروني غير صحيح</span>
                                            </td>
                                        </tr>
                                        <tr>
                                            <td>
                                                <label>
                                                    إسم المستخدم
                                                </label>
                                            </td>
                                            <td>
                                                <div class="form-group has-feedback">
                                                    <input class="form-control" data-val="true" data-val-required="المرجوا ادخال اسم المستخدم" id="UserName" name="UserName" placeholder="إسم المستخدم" type="text" value="" />
                                                    <span class="glyphicon glyphicon-envelope form-control-feedback"></span>
                                                </div>
                                            </td>
                                        </tr>
                                        <tr>
                                            <td>
                                                <label>
                                                    كلمة المرور
                                                </label>
                                            </td>
                                            <td>
                                                <div class="form-group has-feedback">
                                                    <input class="form-control" data-val="true" data-val-required="المرجوا ادخال كلمة المرور" id="Password" name="Password" placeholder="كلمة المرور" type="password" />
                                                    <span class="fa fa-lock form-control-feedback"></span>
                                                </div>
                                            </td>
                                        </tr>
                                        <tr>
                                            <td colspan="2">
                                                <div>

<script type="text/javascript">
$(function () {$('#21514787334c414a8f3a29e319951746').show();})
function ______dcb3b6419de44aafbcc4bd61d3a46705________() { $('#21514787334c414a8f3a29e319951746').hide(); $.post("/moutamadris/DefaultCaptcha/Refresh", { t: $('#CaptchaDeText').val(), __m__: "0" }, function(){$('#21514787334c414a8f3a29e319951746').show();}); return false; }</script> 
<br/>
<img id="CaptchaImage" src="/moutamadris/DefaultCaptcha/Generate?t=c904e5c3349c48cab018dd0fe4669b1e"/><input id="CaptchaDeText" name="CaptchaDeText" type="hidden" value="c904e5c3349c48cab018dd0fe4669b1e" /> <br/><a href="#CaptchaImage" id="21514787334c414a8f3a29e319951746" onclick="______dcb3b6419de44aafbcc4bd61d3a46705________()" style="display:none;">تجديد</a><br/>الجواب هو<br/><input autocomplete="off" autocorrect="off" data-val="true" data-val-required="الرمز لايتطابق مع الصورة" id="CaptchaInputText" name="CaptchaInputText" type="text" value="" /><br/><input data-val="true" data-val-number="The field CleCaptcha must be a number." id="CleCaptcha" name="CleCaptcha" type="hidden" value="1" />                                                        <br />
                                                        <p class="Error">   </p>
                                                </div>
                                            </td>
                                        </tr>
                                        <tr>
                                            <td colspan="2">
                                                <div class="">
                                                    <button type="submit" class="btn btn-primary btn-block btn-flat" style="background: #004b67 !important;color: white !important;border: none !important;width: 90px;">تسجيل الدخول </button>
                                                </div>
                                            </td>
                                        </tr>

                                    </tbody>
                                </table>
                            </div>
                            <div class="col-md-8">

                            </div>
</form>                    </div>
                </td>
                <td class="SliderESP">
                    <img src="/moutamadris/images/slider2.jpg" width="650" height="295" alt="">
                </td>
            </tr>
        </tbody>
    </table>
    <div class="col-md-12 col-xs-12">
        <p style="text-align: center;padding: 10px;font-size: 20px;color: red;">لتفعيل حسابكم يجب استعمال القن السري الأولي المسلم لكم من طرف إدارة مؤسستكم</p>
    </div>




<script>
    $(document).ready(function () {
        window.history.pushState({}, document.title, "/moutamadris/Account");
    })
</script>
                    </div>
                </div>

            </section><!-- /.content -->
        </div><!-- /.content-wrapper -->
        <footer class="main-footer">
            <div class="pull-right hidden-xs">
                <b>Version</b> 2.0
            </div>
            <strong>Copyright &copy; 2018 </strong>
        </footer>

        






    <div id="Model_msg" class="modal" tabindex="-1">
        <div class="modal-dialog">
            <div class="modal-content">
                <div   id="Model_msg_Class"  class="modal-success">
                    <div class="modal-header">

                        <button class="close" aria-label="Close" type="button" data-dismiss="modal"><span aria-hidden="true">×</span></button>
                        <h4 id="Model_msg_Header_title" class="modal-title">Modal Primary</h4>
                    </div>
                </div>
                <div class="modal-body modal-dialog-body">
                    <p id="Model_msg_body"></p>
                </div>
                <div class="modal-footer">

                    <button id="Model_msg_Btn" class="btn  btn-primary" data-dismiss="modal" type="button">إغلاق</button>
                </div>
            </div><!-- /.modal-content -->
        </div><!-- /.modal-dialog -->
    </div>



    </div>




    <script src="/moutamadris/Scripts/jquery.globalize/jquery.validate.globalize.js"></script>






    <!-- Add by ahamdaoui -->
    <!-- 1. Config du composant datepicker -->
    <!-- 2. Resolution du PB de validation des champs de types decimal et date -->
    <script type="text/javascript">

        $(".btnEleve").click(function () {
            if (location.href.indexOf("/moutamadris/General/Home") < 0) {
                var codeEleve = $(this).data('code');
                location.href = '/moutamadris/General/Home' + '?CodeEleve=' + codeEleve;
            }
        })

        $(document).ready(function () {

            //if (lang == 'fr')
            //    $("#loadingDiv").css('left', '230px');


            $(document).on('hidden.bs.modal', function () {
                $('body').css('padding-right', 0);
            })

            $(document).on('hidden.bs.shown', function () {
                $('body').css('padding-right', 0);
            })

            $('.date .form-control').datepicker({
                language: lang,
                format: 'dd/mm/yyyy',
                autoclose: true,
                todayHighlight: true,
                forceParse: false,

            });
        });



        //affichage du waiter pour les ajax calls (loading...)
        $(document).on({
            ajaxSend: function (event, xhr, options) {
                $('body').addClass('loading');
            },
            ajaxStop: function () {
                $('body').removeClass('loading');
            },
            ajaxError: function (xhr, props) {
                $('body').removeClass('loading');


                if (props.status == 401 || props.status == 405) {

                    location.reload();
                    return;
                }

                if (props.status == 403) {
                    $.errorMessageBox('Error', 'Accès non autorisé !!!!!!!');
                    return;
                }



                if (props.status != 200) {
                    $.errorMessageBox('Error', 'حدث خطأ أثناء تنفيذ هذه العملية  , يرجى إعادة المحاولة لاحقا');
                }



            }
        });




        Globalize.culture(culture);

        $.validator.methods.number = function (value, element) {
            return this.optional(element) || jQuery.isNumeric(Globalize.parseFloat(value));
        }

        $.validator.methods.date = function (value, element) {
            //This is not ideal but Chrome passes dates through in ISO1901 format regardless of locale
            //and despite displaying in the specified format.
            return this.optional(element)
                || Globalize.parseDate(value, "dd/mm/yyyy", culture)
                || Globalize.parseDate(value, "yyyy-mm-dd");
        }

    </script>



    <script>
        (function (i, s, o, g, r, a, m) {
            i['GoogleAnalyticsObject'] = r; i[r] = i[r] || function () {
                (i[r].q = i[r].q || []).push(arguments)
            }, i[r].l = 1 * new Date(); a = s.createElement(o),
                m = s.getElementsByTagName(o)[0]; a.async = 1; a.src = g; m.parentNode.insertBefore(a, m)
        })(window, document, 'script', 'https://www.google-analytics.com/analytics.js', 'ga');

        ga('create', 'UA-80043752-7', 'auto');
        ga('send', 'pageview');

    </script>


    


</body>

</html>
