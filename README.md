<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SmartRide Login</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1 class="smart-text">Smart <span class="ride-text">ride.</span></h1>
        <p class="first-line">Your journey starts here.</p>
        <p class="second-line">Connecting you to the best rides.</p>
        <h2 class="login-heading">Login</h2>
        
        <div class="input-container">
            <div class="country-select">
                <div class="selected-country" id="selectedCountry">
                    <span class="country-flag">🇮🇳</span>
                    <span class="country-name">India</span>
                </div>
                <div class="country-dropdown" id="countryDropdown">
                    <input type="text" id="countrySearch" placeholder="Search country..." class="country-search" />
                    <div class="country-option" data-value="91">
                        <span class="country-flag">🇮🇳</span>
                        <span class="country-name">India</span>
                    </div>
                    <div class="country-option" data-value="1">
                        <span class="country-flag">🇺🇸</span>
                        <span class="country-name">USA</span>
                    </div>
                    <div class="country-option" data-value="44">
                        <span class="country-flag">🇬🇧</span>
                        <span class="country-name">UK</span>
                    </div>
                    <div class="country-option" data-value="61">
                        <span class="country-flag">🇦🇺</span>
                        <span class="country-name">Australia</span>
                    </div>
                    <div class="country-option" data-value="49">
                        <span class="country-flag">🇩🇪</span>
                        <span class="country-name">Germany</span>
                    </div>
                    <div class="country-option" data-value="33">
                        <span class="country-flag">🇫🇷</span>
                        <span class="country-name">France</span>
                    </div>
                    <div class="country-option" data-value="39">
                        <span class="country-flag">🇮🇹</span>
                        <span class="country-name">Italy</span>
                    </div>
                    <div class="country-option" data-value="34">
                        <span class="country-flag">🇪🇸</span>
                        <span class="country-name">Spain</span>
                    </div>
                    <div class="country-option" data-value="55">
                        <span class="country-flag">🇧🇷</span>
                        <span class="country-name">Brazil</span>
                    </div>
                    <div class="country-option" data-value="52">
                        <span class="country-flag">🇲🇽</span>
                        <span class="country-name">Mexico</span>
                    </div>
                    <div class="country-option" data-value="31">
                        <span class="country-flag">🇳🇱</span>
                        <span class="country-name">Netherlands</span>
                    </div>
                    <div class="country-option" data-value="46">
                        <span class="country-flag">🇸🇪</span>
                        <span class="country-name">Sweden</span>
                    </div>
                    <div class="country-option" data-value="47">
                        <span class="country-flag">🇳🇴</span>
                        <span class="country-name">Norway</span>
                    </div>
                    <div class="country-option" data-value="45">
                        <span class="country-flag">🇩🇰</span>
                        <span class="country-name">Denmark</span>
                    </div>
                    <div class="country-option" data-value="358">
                        <span class="country-flag">🇫🇮</span>
                        <span class="country-name">Finland</span>
                    </div>
                    <div class="country-option" data-value="81">
                        <span class="country-flag">🇯🇵</span>
                        <span class="country-name">Japan</span>
                    </div>
                    <div class="country-option" data-value="82">
                        <span class="country-flag">🇰🇷</span>
                        <span class="country-name">South Korea</span>
                    </div>
                    <div class="country-option" data-value="65">
                        <span class="country-flag">🇸🇬</span>
                        <span class="country-name">Singapore</span>
                    </div>
                    <div class="country-option" data-value="63">
                        <span class="country-flag">🇵🇭</span>
                        <span class="country-name">Philippines</span>
                    </div>
                    <div class="country-option" data-value="27">
                        <span class="country-flag">🇿🇦</span>
                        <span class="country-name">South Africa</span>
                    </div>
                    <div class="country-option" data-value="971">
                        <span class="country-flag">🇦🇪</span>
                        <span class="country-name">UAE</span>
                    </div>
                    <div class="country-option" data-value="852">
                        <span class="country-flag">🇭🇰</span>
                        <span class="country-name">Hong Kong</span>
                    </div>
                    <div class="country-option" data-value="66">
                        <span class="country-flag">🇹🇭</span>
                        <span class="country-name">Thailand</span>
                    </div>
                    <div class="country-option" data-value="60">
                        <span class="country-flag">🇲🇾</span>
                        <span class="country-name">Malaysia</span>
                    </div>
                    <div class="country-option" data-value="62">
                        <span class="country-flag">🇮🇩</span>
                        <span class="country-name">Indonesia</span>
                    </div>
                    <div class="country-option" data-value="84">
                        <span class="country-flag">🇻🇳</span>
                        <span class="country-name">Vietnam</span>
                    </div>
                    <div class="country-option" data-value="351">
                        <span class="country-flag">🇵🇹</span>
                        <span class="country-name">Portugal</span>
                    </div>
                    <div class="country-option" data-value="353">
                        <span class="country-flag">🇮🇪</span>
                        <span class="country-name">Ireland</span>
                    </div>
                    <div class="country-option" data-value="43">
                        <span class="country-flag">🇦🇹</span>
                        <span class="country-name">Austria</span>
                    </div>
                    <div class="country-option" data-value="41">
                        <span class="country-flag">🇨🇭</span>
                        <span class="country-name">Switzerland</span>
                    </div>
                    <div class="country-option" data-value="64">
                        <span class="country-flag">🇳🇿</span>
                        <span class="country-name">New Zealand</span>
                    </div>
                    <div class="country-option" data-value="56">
                        <span class="country-flag">🇨🇱</span>
                        <span class="country-name">Chile</span>
                    </div>
                    <div class="country-option" data-value="57">
                        <span class="country-flag">🇨🇴</span>
                        <span class="country-name">Colombia</span>
                    </div>
                    <div class="country-option" data-value="54">
                        <span class="country-flag">🇦🇷</span>
                        <span class="country-name">Argentina</span>
                    </div>
                    <div class="country-option" data-value="51">
                        <span class="country-flag">🇵🇪</span>
                        <span class="country-name">Peru</span>
                    </div>
                    <div class="country-option" data-value="593">
                        <span class="country-flag">🇪🇨</span>
                        <span class="country-name">Ecuador</span>
                    </div>
                    <div class="country-option" data-value="598">
                        <span class="country-flag">🇺🇾</span>
                        <span class="country-name">Uruguay</span>
                    </div>
                    <div class="country-option" data-value="972">
                        <span class="country-flag">🇮🇱</span>
                        <span class="country-name">Israel</span>
                    </div>
                    <div class="country-option" data-value="7">
                        <span class="country-flag">🇷🇺</span>
                        <span class="country-name">Russia</span>
                    </div>
                    <div class="country-option" data-value="90">
                        <span class="country-flag">🇹🇷</span>
                        <span class="country-name">Turkey</span>
                    </div>
                    <div class="country-option" data-value="359">
                        <span class="country-flag">🇧🇬</span>
                        <span class="country-name">Bulgaria</span>
                    </div>
                    <div class="country-option" data-value="420">
                        <span class="country-flag">🇨🇿</span>
                        <span class="country-name">Czech Republic</span>
                    </div>
                    <div class="country-option" data-value="421">
                        <span class="country-flag">🇸🇰</span>
                        <span class="country-name">Slovakia</span>
                    </div>
                    <div class="country-option" data-value="40">
                        <span class="country-flag">🇷🇴</span>
                        <span class="country-name">Romania</span>
                    </div>
                    <div class="country-option" data-value="36">
                        <span class="country-flag">🇭🇺</span>
                        <span class="country-name">Hungary</span>
                    </div>
                    <div class="country-option" data-value="30">
                        <span class="country-flag">🇬🇷</span>
                        <span class="country-name">Greece</span>
                    </div>
                    <div class="country-option" data-value="385">
                        <span class="country-flag">🇭🇷</span>
                        <span class="country-name">Croatia</span>
                    </div>
                    <div class="country-option" data-value="370">
                        <span class="country-flag">🇱🇹</span>
                        <span class="country-name">Lithuania</span>
                    </div>
                    <div class="country-option" data-value="371">
                        <span class="country-flag">🇱🇻</span>
                        <span class="country-name">Latvia</span>
                    </div>
                    <div class="country-option" data-value="386">
                        <span class="country-flag">🇸🇮</span>
                        <span class="country-name">Slovenia</span>
                    </div>
                    <div class="country-option" data-value="372">
                        <span class="country-flag">🇪🇪</span>
                        <span class="country-name">Estonia</span>
                    </div>
                    <div class="country-option" data-value="354">
                        <span class="country-flag">🇮🇸</span>
                        <span class="country-name">Iceland</span>
                    </div>
                    <div class="country-option" data-value="389">
                        <span class="country-flag">🇲🇰</span>
                        <span class="country-name">North Macedonia</span>
                    </div>
                    <div class="country-option" data-value="373">
                        <span class="country-flag">🇲🇩</span>
                        <span class="country-name">Moldova</span>
                    </div>
                </div>
            </div>
            <div class="phone-number-container">
                <span class="country-code" id="countryCode">+91</span>
                <input type="text" id="phoneNumber" placeholder="Enter phone number" class="phone-input" />
            </div>
        </div>

        

   <!-- Continue button container -->
<div class="button-container">
    <button class="continue-button" id="continueBtn">Continue</button>
    <div class="or-text">or</div>
</div>
<!-- Terms and Policies section -->
<div class="terms-container">
    <p class="terms-line">By continuing, you agree to our</p>
    <p class="terms-links">
        <a href="terms-of-service-url" class="terms-link">Terms of Service</a>, 
        <a href="privacy-policy-url" class="terms-link">Privacy Policy</a>, 
        and 
        <a href="content-policy-url" class="terms-link">Content Policy</a>.
    </p>
</div>



<script src="script.js"></script>
</body>
</html>
