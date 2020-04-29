# The-Rt-in-Wuhan
Method

We repeated the process of calculating Rt in Wuhan in the Article published in JAMA [1] by using the methodology described elsewhere [2].
In brief, we adjusted the methodology presented in references [3-4] to account for case importations. Considering the same parameter for serial interval as 7.5 days (SD: 3.4 days), we run 1,000,000 iterations with non-informative prior distributions of Rt (flat distribution in the range (0-1000]). The code is freely available at elsewhere (https://github.com/majelli/Rt).

Result

Attached is the figure for Rt, and detailed result refer to the csv file in repository.

Reference
1.	Pan A, Liu L, Wang C, et al. Association of Public Health Interventions With the Epidemiology of the COVID-19 Outbreak in Wuhan, China [J]. Jama, 2020, e206130. doi:10.1001/jama.2020.6130.
2.	Zhang J, Litvinova M, Wang W, et al. Evolving epidemiology and transmission dynamics of coronavirus disease 2019 outside Hubei province, China: a descriptive and modelling study. Lancet Infect Dis 2020; S1473-3099(20)30230-9. doi:10.1016/S1473-3099(20)30230-9.
3.	Liu Q, Ajelli M, Aleta A, Merler S, Moreno Y, Vespignani A. Measurability of the epidemic reproduction number in data-driven contact networks. Proc Natl Acad Sci 2018;115(50):12680.
4.	World Health Organization Ebola Response Team, Aylward B, Barboza P, et al. Ebola virus disease in West Africa--the first 9 months of the epidemic and forward projections. N Engl J Med 2014;371(16):1481-95.
