<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Email Signature Generator</title>
<style>
  body { font-family: Verdana, sans-serif; }
  .input-wrapper { margin-top: 10px; display: flex; align-items: center; }
  input, button { }
  label { margin-right: 10px; }
  input[type="checkbox"] { margin-right: 5px; }
  input[type="text"] { flex: 1; }
  button { margin-top: 20px; }
  a {
  color: inherit;
  text-decoration: none; 
  border: none;
}
</style>
</head>
<body>
<h1>1. Fill the form</h1>
<div id="signatureForm">
  <!-- Configuration for each field with a checkbox to enable it -->
  <div class="input-wrapper">
    <input type="checkbox" id="enableName">
    <label for="name">Name:</label>
    <input type="text" id="name" placeholder="Enter your name" disabled>
  </div>

  <div class="input-wrapper">
    <input type="checkbox" id="enablePosition">
    <label for="position">Position:</label>
    <input type="text" id="position" placeholder="Enter your position" disabled>
  </div>

  <div class="input-wrapper">
    <input type="checkbox" id="enablePhone">
    <label for="phone">Phone:</label>
    <input type="text" id="phone" placeholder="Enter your phone number" disabled>
  </div>

  <div class="input-wrapper">
    <input type="checkbox" id="enableEmail">
    <label for="email">Email:</label>
    <input type="text" id="email" placeholder="Enter your email address" disabled>
  </div>

  <div class="input-wrapper">
    <input type="checkbox" id="enableLocation">
    <label for="location">Location:</label>
    <input type="text" id="location" placeholder="Enter your location" disabled>
  </div> 

  <div class="input-wrapper">
    <input type="checkbox" id="enableWebsite">
    <label for="website">Website:</label>
    <input type="text" id="website" placeholder="Example: FortuneBox.com" disabled>
  </div>
  
  
  <h1>2. Preview</h1>

<div id="signature_container" style="width: 550px; padding: 60px 0px;">
  <!-- Signature preview area with icons for each field -->
  <table id="signaturePreview" style="color: rgb(0, 0, 0); font-family: Verdana, serif; width: 100%; padding-bottom: 24px; border-bottom: 1px solid rgb(231, 229, 247);">
    <tbody>
      <tr>
       
        <td style="padding: 0px 20px 0px 0px;">
          <p id="signatureName" style="margin: 0px; font-size: 18px; line-height: 21px; font-weight: 700; display: none;"></p>
          <p id="signaturePosition" style="margin: 0px; font-size: 14px; line-height: 22px; display: none;"></p>
        </td>
        <td style="padding: 0px 0px 0px 40px; border-left: 1px solid rgb(231, 229, 247);">
          <p id="signaturePhone" style="margin: 0px; font-size: 13px; line-height: 29px; display: none;"></p>
          <p id="signatureEmail" style="margin: 0px; font-size: 13px; line-height: 29px; display: none;"></p>
		  <p id="signatureLocation" style="margin: 0px; font-size: 13px; line-height: 29px; display: none;"></p>
		  <p id="signatureWebsite" style="margin: 0px; font-size: 13px; line-height: 29px; display: none;"></p>
        </td>
      </tr>
    </tbody>
  </table>
  <div id="signatureBanner" style="width: 100%; text-align: center; display: none;">
    <img src="" alt="Signature Banner" id="bannerImage" style="width: 100%; max-width: 560px; height: auto;">
  </div>
  <!-- Social icons and logo at the bottom -->
<div style="color: rgb(0, 0, 0); font-family: Arial, serif; max-width: 550px; width: 100%; padding-top: 24px; display: flex; align-items: center;">
  <div style="flex-grow: 1; padding: 0;">
    <a href="https://fortunebox.com" target="_blank">
      <img src="https://i.postimg.cc/SKbJtvtB/fortunebox.png" alt="fortunebox Logo" width="120" height="40" style="width: 120px; height: auto;">
    </a>
  </div>
  <!-- Spacer div to create a gap -->
  <div style="flex-grow: 0; width: 435px; line-height: 50px;"></div>  <!-- Adjust width as needed for gap size -->
  <div style="flex-grow: 1; padding: 0; display: flex; justify-content: flex-end;">
    <a href="https://x.com/fortuneboxcom" target="_blank" style="text-decoration: none; margin-right: 8px;">
      <img src="https://i.postimg.cc/KY7RXD6R/x.png" alt="Twitter" width="25" height="25">
    </a>
    <a href="https://www.instagram.com/fortuneboxcom" target="_blank" style="text-decoration: none; margin-right: 8px;">
      <img src="https://i.postimg.cc/KzZ4mgbQ/ig.png" alt="Instagram" width="25" height="25">
    </a>
    <a href="https://www.facebook.com/fortuneboxcom/" target="_blank" style="text-decoration: none; margin-right: 8px;">
      <img src="https://i.postimg.cc/hjpvvPPn/fb.png" alt="Facebook" width="25" height="25">
    </a>
  </div>
</div>

<script>
document.querySelectorAll('#signatureForm input[type="checkbox"]').forEach(checkbox => {
  checkbox.addEventListener('change', function() {
    const input = this.nextElementSibling.nextElementSibling;
    input.disabled = !this.checked;
    const field = this.id.replace('enable', '').toLowerCase();
    const contentElement = document.getElementById('signature' + field.charAt(0).toUpperCase() + field.slice(1));
    const imgElement = document.getElementById('profileImage');
    const profileCell = document.getElementById('profilePictureCell');

    if (this.checked) {
      if (field === 'profilepicture') {
        profileCell.style.display = 'block';
        imgElement.style.display = 'block';
        input.addEventListener('input', function() {
          imgElement.src = input.value || "https://reply.io/wp-content/uploads/signature-generator-photo-placeholder.png";
        });
      } else {
        contentElement.style.display = 'block';
        input.addEventListener('input', function() {
          let imageUrl;
          switch (field) {
            case 'email':
              imageUrl = "https://i.postimg.cc/5Ytjj5hW/email.png";
              break;
            case 'location':
              imageUrl = "https://i.postimg.cc/5HbXWWp0/address.png";
              break;
			 case 'website':
              imageUrl = "https://i.postimg.cc/njwrmjxj/website.png";
              break;
			 case 'phone':
              imageUrl = "https://i.postimg.cc/1gBf97YK/phone.png";
              break;
            default:
              imageUrl = "https://i.ibb.co/8cWQzd6/name.png";
              break;
          }
          contentElement.innerHTML = '<img src="' + imageUrl + '" width="14" height="14" style="margin-right: 10px;vertical-align: text-top;">' + input.value;
        });
      }
    } else {
      contentElement.style.display = 'none';
      if (field === 'profilepicture') {
        profileCell.style.display = 'none';
        imgElement.style.display = 'none';
        imgElement.src = "";
      }
    }
  });
});

function copySignature() {
  const signature = document.getElementById('signature_container').innerHTML;
  const el = document.createElement('textarea');
  el.value = signature;
  document.body.appendChild(el);
  el.select();
  document.execCommand('copy');
  document.body.removeChild(el);
  alert('Signature copied to clipboard!');
}
</script>
</body>
</html>
