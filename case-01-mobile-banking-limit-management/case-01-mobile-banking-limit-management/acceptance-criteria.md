# Acceptance Criteria – Mobile Banking Limit Management

## AC-01 – Display Transfer Limits

Given that the customer opens the limit management page,  
when the page loads,  
then the system must display EFT, FAST, and internal transfer limits separately.

## AC-02 – Submit Valid Limit Request

Given that the customer enters a valid requested limit,  
when OTP verification is completed successfully,  
then the system must submit the request.

## AC-03 – Prevent Submission After Failed OTP

Given that OTP verification fails,  
when the customer enters an incorrect OTP,  
then the system must display an error message and prevent submission.

## AC-04 – Validate Maximum Threshold

Given that the requested limit exceeds the maximum allowed threshold,  
when the customer submits the request,  
then the system must reject the request or display a validation warning.

## AC-05 – Display Request History

Given that the request is submitted,  
when the customer opens request history,  
then the request status must be visible as Pending, Approved, or Rejected.
