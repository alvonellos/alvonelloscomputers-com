# alvonelloscomputers-com
Alvonellos Computers Website


<div class='row'>
  <div class='col-md-12'>
    <div class='widget-content'>
      <p class="customer-title">Welcome!</p>

      <p>You may begin a check-in to get started with a new request, or check the status of an existing request.</p>
    </div>
  </div>
</div>

<div class='row mts'>
  <div class='col-md-6'>
    <div class='widget-content' style='min-height: 410px;'>
      <h3>Start a New Service Ticket</h3>

      <p>We just need a couple things to get started:</p>

      <div class='get-started'>
        <form class="simple_form new_lead" id="new_lead" autocomplete="off" novalidate="novalidate" action="https://alvonelloscomputers.syncromsp.com/check_ins/ticket_info" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />

            <div class='row'>
              <div class='col-lg-6'>
                <div class="form-group string optional lead_first_name"><label class="string optional" for="lead_first_name">First name</label><input class="string optional form-control" maxlength="255" placeholder="First Name" size="255" type="text" name="lead[first_name]" id="lead_first_name" /></div>
              </div>
              <div class='col-lg-6'>
                <div class="form-group string optional lead_last_name"><label class="string optional" for="lead_last_name">Last name</label><input class="string optional form-control" maxlength="255" placeholder="Last Name" size="255" type="text" name="lead[last_name]" id="lead_last_name" /></div>
              </div>
            </div>
            <div class="form-group tel optional lead_phone"><label class="tel optional" for="lead_phone">Phone</label><input class="string tel optional form-control form-control" maxlength="255" placeholder="Phone" type="tel" size="255" name="lead[phone]" id="lead_phone" /></div>
            <div class="form-group email optional lead_email"><label class="email optional" for="lead_email">Email</label><input class="string email optional form-control form-control" maxlength="255" placeholder="Email" type="email" size="255" name="lead[email]" id="lead_email" /></div>
            
            

            <div class="row">
              <div class="col-lg-6 col-md-6">
                
              </div>
              <div class="col-lg-6 col-md-6">
                
              </div>
            </div>

            <input type="submit" name="commit" value="Get Started" class="btn btn-sm  btn-success mtm" data-disable-with="Get Started" />
</form>      </div>
    </div>
  </div>
  <div class='col-md-6'>
    <div class='widget-content' style='min-height: 410px;'>
      <h3 class=''>Existing Ticket Lookup</h3>
      <p>Just enter your info to do a search.</p>

      <div class='get-started'>
        <form autocomplete="off" novalidate="novalidate" class="simple_form check_existing" action="https://alvonelloscomputers.syncromsp.com/check_ins/check_existing" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="d5FIc43vwHEP2BcjnwZ3K9+uImvdcz5xP0Wi8H4goS54/nZRN+KJgzS4+vlQSCsGYI1j3J9jiOoTUintOCThfA==" />
            <div class="form-group string required check_existing_ticket_number"><label class="string required" for="check_existing_ticket_number"><abbr title="required">*</abbr> Ticket number</label><input class="string required form-control" placeholder="eg, 1234" type="text" name="check_existing[ticket_number]" id="check_existing_ticket_number" /></div>
            <div class="form-group string required check_existing_last_name"><label class="string required" for="check_existing_last_name"><abbr title="required">*</abbr> Last name</label><input class="string required form-control" placeholder="Last Name" type="text" name="check_existing[last_name]" id="check_existing_last_name" /></div>
            <input type="submit" name="commit" value="Lookup" class="btn btn-sm btn-success mtm" data-disable-with="Lookup" />
</form>      </div>
    </div>
  </div>
</div>
