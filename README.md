# goit-markup-hw-01
.activity-text {
        
    margin: 0;
    padding-top: 27px;
    padding-bottom: 27px;

    font-size: 14px;
    line-height: 1.14;
    text-align: center;
    letter-spacing: 0.03em;
    text-transform: uppercase;
    color: #240f0f;

}

@media screen and (min-width: 768px) {
    flex-basis: calc((100% - 2 * 30px) / 2);
  }

  @media screen and (min-width: 1200px) {
    flex-basis: calc((100% - 3 * 30px) / 3);
  }




.feature__item {
  @media screen and (max-width: 767px) {
    &:not(:last-child) {
      margin-bottom: 30px;
    }
  }

  @media screen and (min-width: 768px) {
    margin: 15px;
  }

  @media screen and (min-width: 768px) and (max-width: 1199px) {
    width: 354px;
  }

  @media screen and (min-width: 1200px) {
    width: 270px;
  }
}
