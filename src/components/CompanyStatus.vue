<template>
    <section class="company-status contentLoad">
            <div class="container">
              <div class="row helpLine">
                <div class="col-md-7 inner-helpline">
                </div>
                <div class="col-md-5 inner-helpline">
                    <div class="helpLine-Content">
                       <div class="heading-info">
                            <h1 class="theme-main-heading">Montgomery</h1>
                            <h2>Fire Department</h2>
                            <p class="color-orange">Call Volume</p>
                       </div>
                    </div>
                    <div class="servicesReport">
                        <div class="reportValue">
                            <span class="value color-orange count percent" data-count="906">0</span>
                            <span class="Year">2017</span>
                            <span class="KeyValue">Calls</span>
                        </div>
                        <div class="reportValue">
                            <span class="value color-orange count percent" data-count="500">0</span>
                            <span class="Year">2018</span>
                            <span class="KeyValue">Calls</span>
                        </div>
                        <div class="reportValue">
                            <span class="value color-orange count percent" data-count="128">0</span>
                            <span class="KeyValue">Calls<br>YEAR-TO-DATE</span>
                        </div>
                        <div class="reportValue">
                            <span class="value color-orange count percent" data-count="8">0</span>
                            <span class="KeyValue">Calls<br>THIS MONTH</span>
                        </div>
                    </div>
                </div>
              </div>
            </div>
        </section>
</template>

<script>
export default {
    name : 'CompanyStats'
}
</script>

<style>
section.company-status .helpLine {}
section.company-status .helpLine .inner-helpline {
    display: grid;
    place-content: center;
}
section.company-status .helpLine .inner-helpline .helpLine-Content {padding-bottom: 3rem;}
section.company-status .helpLine .inner-helpline .helpLine-Content .heading-info {
    color: #fff;
    text-align: center;
}
section.company-status .helpLine .inner-helpline .helpLine-Content .heading-info h1 {
    font-size: 4.5rem;
}
section.company-status .helpLine .inner-helpline .helpLine-Content .heading-info h2 {
    font-size: 3.5rem;
}
section.company-status .helpLine .inner-helpline .helpLine-Content .heading-info p {
    font-size: 2.5rem;
}
section.company-status .helpLine .inner-helpline .servicesReport {display: flex;flex-wrap: wrap;}
section.company-status .helpLine .inner-helpline .servicesReport .reportValue {
    flex: 0 1 50%;
    text-align: center;
    font-size: 2.5rem;
    border: 1px solid #d87001a6;
    display: flex;
    flex-direction: column;
    color: #fff;
    padding-bottom: 3rem;
    padding-top: 1.5rem;
}
section.company-status .helpLine .inner-helpline .servicesReport .reportValue span.value {
    font-size: 4.5rem;
}
section.company-status .helpLine .inner-helpline .servicesReport .reportValue span.Year {
    font-size: 2rem;
    font-weight: 300;
}
section.company-status .helpLine .inner-helpline .servicesReport .reportValue span.KeyValue {
    font-size: 2.1rem;
    font-weight: 300;
    text-transform: uppercase;
}
section.company-status .helpLine .inner-helpline .servicesReport .reportValue:nth-child(1) {
    border: 0;
}
section.company-status .helpLine .inner-helpline .servicesReport .reportValue:nth-child(2) {
    border-width: 0px 0px 0px 1px;
}
section.company-status .helpLine .inner-helpline .servicesReport .reportValue:nth-child(3) {
    border-width: 1px 0px 0px 0;
}
section.company-status .helpLine .inner-helpline .servicesReport .reportValue:nth-child(4) {
    border-width: 1px 0px 0 1px;
}
</style>