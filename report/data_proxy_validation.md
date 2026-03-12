## 1. Proxy Validation: Pew(Youtube) vs Kaggle (Telco)
- **Churn Rate By Income** 
    - Pew(YouTube): Low (77) < Medium (84) < High (87)
    - Telco: Low (60) < Medium (76) < High (83)
- **Gender**
    - Pew(YouTube): Women (83) < Men (86)
    - Telco churn: Women (73) > Men (74)
- **Age Group** 
    - Pew YouTube usage - Ages 18-29 (95%) vs 65+ (64%) = 31% difference
    - Telco: SeniorCitizen 0/1 comparison --> Older age expected lower churn
- **Strong Validation** 
    - Pew(YouTube): Older = Lower (65+ 64%)
    - Telco: Older = Lower (Senior 58.32%)
<div align="center>
    <table border="0">
        <tr>
            <td><img src="outputs/proxy_validation_images/outlier_median.png" width="200"></td>
            <td><img src="outputs/proxy_validation_images/tenure_outliers.png" width="200"></td>
            <td><img src="outputs/proxy_validation_images/churn_rate_byIncome.png" width="150" height="100"></td>
            <td><img src="outputs/proxy_validation_images/gender.png" width="150" height="100"></td>
            <td><img src="outputs/proxy_validation_images/age.png" width="150" height="100"></td>
        </tr>
    </table>
</div>
