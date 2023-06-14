# zadanie2
a)zmodyfikować kod źródłowy tak by aplikacja wyświetlała imię oraz nazwisko studenta
(tekst pod symbolem „atomu”)
![image](https://github.com/JSakowski15/zadanie2/assets/133519661/0cbcc104-3a34-4938-9946-ea34850d653d)

b)opracować łańcuch działań w ramach Github Actions, który pozwoli na zbudowaniu
obrazów Docker zgodnych z OCI dla dwóch architektur sprzętowych: x86_64 oraz arm64
(procesor M1/M2)
![image](https://github.com/JSakowski15/zadanie2/assets/133519661/4a700f93-67a6-4cc3-a9e7-90d36449e3f8)
![image](https://github.com/JSakowski15/zadanie2/assets/133519661/1c866aaa-b373-470f-9037-7df11085092c)

c)obraz ma zostać poddany testowi pod kątem CVE z wykorzystaniem dowolnego (jednego
z trzech) narzędzi przedstawionych na końcu instrukcji do laboratorium nr 12. Obraz nie
może mieć żadnych zagrożeń krytycznych. 
![image](https://github.com/JSakowski15/zadanie2/assets/133519661/8210eea2-958e-458c-b06c-3593b6e3fe77)
![image](https://github.com/JSakowski15/zadanie2/assets/133519661/a1dd04d9-a82a-4a85-8ba1-40dd9730b523)
Nie wykryto żadnych błędów krytycznych, jedynie pojawiły się ostrzeżenia i błędy niskiego poziomu.

d)w trakcie budowania obrazów należy korzystać z cache w trybie inline
![image](https://github.com/JSakowski15/zadanie2/assets/133519661/09a10bc8-71bb-44b2-ab43-e6b0c92a2503)
![image](https://github.com/JSakowski15/zadanie2/assets/133519661/46c4a949-3bec-46d1-986f-883d7490a2a7)
![image](https://github.com/JSakowski15/zadanie2/assets/133519661/375ec64f-dc98-42a9-8af6-e2e227e14117)

e)po zbudowaniu, w ramach działań w Github Actions, obraz ma być przesłany do
repozytorium na Github Packages (repo: ghcr.io)
![image](https://github.com/JSakowski15/zadanie2/assets/133519661/7e051e2f-1d30-49e1-9391-cf3ee157f560)


Sprawdzenie poprawności działania "github action"
![image](https://github.com/JSakowski15/zadanie2/assets/133519661/cb4ecd43-6066-4cd0-bc20-37e1a3e30670)
![image](https://github.com/JSakowski15/zadanie2/assets/133519661/b9126de2-4221-47a4-b842-0cb78906b24a)


Pobranie obrazu za pomocą ghcr.io
![image](https://github.com/JSakowski15/zadanie2/assets/133519661/6c724020-4b8f-4a5b-a014-04f6ae380b44)

Uruchomienie:
![image](https://github.com/JSakowski15/zadanie2/assets/133519661/ce57fbed-a590-4422-858d-5a713ddbec18)
![image](https://github.com/JSakowski15/zadanie2/assets/133519661/077ca569-e763-421d-bfb9-3f6d9fc94035)
![image](https://github.com/JSakowski15/zadanie2/assets/133519661/2cb4db9d-e395-44ae-b8b3-fcddf99e4b77)

Zakończenie pracy:
![image](https://github.com/JSakowski15/zadanie2/assets/133519661/0d526485-bae4-4654-91e9-8b7e098a6ed9)


Pomoce naukowe (źródła) oraz materiały użyte w powyższej pracy:
Pliki dołączone do laboratorium 12 na moodle;
https://docs.github.com/en/actions/publishing-packages/publishing-docker-images;
https://docs.snyk.io/integrations/ci-cd-integrations/github-actions-integration/snyk-docker-action;


